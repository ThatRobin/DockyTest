# Condition JSON Format
This is the format of a JSON file describing an action. These can be used in place of creating an action inside of an origin. 

Action JSON files need to be placed inside the `data/<namespace>/{Action Type}` folder of your datapack. Where the `{Action Type}` is either `entity`, `bientity`, `block` or `item`.
### Examples
```json
{
  "type": "apoli:sneaking"
}
```
This example is a condition that checks if the player is sneaking.
```json
{
  "type": "apoli:active_self",
  "entity_action": {
    "type": "origins:add_velocity",
    "y": 2
  },
  "condition": {
    "type": "ra_additions:evaluate_condition",
    "entity_condition": "ra_additions:condition_example_1"
  },
  "cooldown": 20,
  "hud_render": {
    "should_render": false
  }
}
```
This is an example of one way that you can use an entity condition from a file
