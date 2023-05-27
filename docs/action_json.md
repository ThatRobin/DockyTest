# Action JSON Format
This is the format of a JSON file describing an action. These can be used in place of creating an action inside of an origin. 

Action JSON files need to be placed inside the `data/<namespace>/{Action Type}` folder of your datapack. Where the `{Action Type}` is either `entity`, `bientity`, `block` or `item`.
### Examples
```json
{
  "type": "origins:add_velocity",
  "y": 2
}
```
This example is an action that launches the player into the air.
```json
{
  "type": "apoli:active_self",
  "entity_action": {
    "type": "origins:raycast",
    "distance": 16,
    "block": true,
    "entity": true,
    "shape_type": "visual",
    "fluid_handling": "any",
    "bientity_action": {
      "type": "origins:target_action",
      "action": {
        "type": "origins:execute_command",
        "command": "say I\u0027ve been hit!"
      }
    },
    "block_action": {
      "type": "origins:execute_command",
      "command": "say Block (hit)"
    },
    "entityblock_action": {
      "type": "ra_additions:mimic_item_on_block",
      "item_stack": {
        "item": "minecraft:flint_and_steel"
      }
    },
    "before_action": {
      "type": "origins:execute_command",
      "command": "say Before"
    },
    "hit_action": {
      "type": "origins:execute_command",
      "command": "say After (hit)"
    },
    "miss_action": {
      "type": "origins:execute_command",
      "command": "say After (miss)"
    },
    "command_at_hit": "particle minecraft:block_marker minecraft:emerald_block ~ ~ ~ 0 0 0 0.0 1 normal @a",
    "command_along_ray": "particle minecraft:soul_fire_flame",
    "command_step": 1,
    "command_along_ray_only_on_hit": true
  },
  "cooldown": 20,
  "hud_render": {
    "should_render": false
  },
  "key": {
    "key": "key.use"
  }
}
```
This is an example of one way that you can use an entity action from a file
