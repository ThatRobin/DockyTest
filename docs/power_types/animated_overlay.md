# Animated Overlay
[Power Types](../power_types.md)

Lets you have a texture overlay onto the entity that you can have change over time.

Type ID: `ra_additions:animated_overlay`
### Fields
 | Field | Type | Default | Description | 
|---|---|---|---|
 | `interval` | [Int](../data_types/int.md) | _optional_ |  | 
 | `texture_location` | [Array](../data_types/array.md) of [Identifier](../data_types/identifier.md) | _optional_ |  | 
 | `texture_locations` | [Array](../data_types/array.md) of [Identifier](../data_types/identifier.md) | _optional_ |  | 

### Example
```json
{
  "type": "ra_additions:animated_overlay",
  "textures": [
    "minecraft:textures/models/armor/diamond_layer_1.png"
  ]
}
```
This example will make the player look like they are wearing some diamond armour.
