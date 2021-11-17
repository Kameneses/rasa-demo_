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

## interactive_story_1
* saludo
    - utter_saludo
    - utter_ask_pokemon
* buscar_pokemon{"nombre_pokemon": "Mew"}
    - slot{"nombre_pokemon": "Mew"}
    - action_buscar_pokemon
    - reset_slots

## New Story

* saludo
    - utter_saludo
    - utter_ask_pokemon
* buscar_pokemon{"nombre_pokemon":"Pikachu"}
    - slot{"nombre_pokemon":"Pikachu"}
    - action_buscar_pokemon

## New Story

* saludo
    - utter_saludo
    - utter_ask_pokemon
* buscar_pokemon{"nombre_pokemon":"Castform"}
    - slot{"nombre_pokemon":"Castform"}
    - action_buscar_pokemon

## New Story

* buscar_pokemon{"numero_pokemon":"151"}
    - slot{"numero_pokemon":"151"}
    - action_buscar_pokemon

## New Story

* saludo
    - utter_saludo
    - utter_ask_pokemon
* buscar_pokemon{"nombre_pokemon":"Alomomola"}
    - slot{"nombre_pokemon":"Alomomola"}
    - action_buscar_pokemon

## New Story

* buscar_pokemon{"nombre_pokemon":"Entei"}
    - slot{"nombre_pokemon":"Entei"}
    - action_buscar_pokemon

## New Story

* buscar_pokemon{"numero_pokemon":"314"}
    - slot{"numero_pokemon":"314"}
    - action_buscar_pokemon

## New Story

* buscar_pokemon{"numero_pokemon":"1200"}
    - slot{"numero_pokemon":"1200"}
    - action_buscar_pokemon
* buscar_pokemon{"numero_pokemon":"1001"}
    - slot{"numero_pokemon":"1001"}
    - action_buscar_pokemon
* buscar_pokemon{"numero_pokemon":"950"}
    - slot{"numero_pokemon":"950"}
    - action_buscar_pokemon
* buscar_pokemon{"numero_pokemon":"800"}
    - slot{"numero_pokemon":"800"}
    - action_buscar_pokemon
* buscar_pokemon{"nombre_pokemon":"Necrozma"}
    - slot{"nombre_pokemon":"Necrozma"}
    - action_buscar_pokemon
