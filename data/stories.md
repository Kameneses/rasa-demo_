## buscar pokemon por nombre 1
* buscar_pokemon
  - utter_ask_pokemon
* buscar_pokemon{"nombre_pokemon": "Ivysaur"}
  - action_buscar_pokemon

## buscar pokemon por número 1
* buscar_pokemon
  - utter_ask_pokemon
* buscar_pokemon{"numero_pokemon": "41"}
  - action_buscar_pokemon

## buscar pokemon por nombre 2
* buscar_pokemon{"nombre_pokemon": "Ivysaur"}
  - action_buscar_pokemon

## buscar pokemon por número 2
* buscar_pokemon{"numero_pokemon": "41"}
  - action_buscar_pokemon

## saludo
* saludo
  - utter_saludo
  - utter_ask_pokemon

## start
* start
  - utter_saludo
  - utter_ask_pokemon

## interactive_story_1
* saludo
    - utter_saludo
    - utter_ask_pokemon
* buscar_pokemon
    - utter_ask_pokemon
* buscar_pokemon{"nombre_pokemon": "Charmander"}
    - slot{"nombre_pokemon": "Charmander"}
    - action_buscar_pokemon
    - reset_slots
* saludo
    - utter_saludo
