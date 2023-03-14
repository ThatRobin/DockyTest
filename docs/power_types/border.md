# Border
[Power types Type](../power_types_types.md)

Creates a border around the entity with this power. Only entities that fulfil the conditions may pass through it.

Type ID: `ra_additions:border`
### Fields
Field | Type | Default | Description
------|------|---------|-------------
`border_texture` | [Identifier](../data_types/identifier.md) | minecraft:textures/misc/forcefield.png | The texture used on the border.
`entity_condition` | [Entity condition](../data_types/entity_condition.md) | _optional_ | If specified, if the entity colliding with the border fulfils the condition, it can walk through the border.
`bientity_condition` | [Bientity condition](../data_types/bientity_condition.md) | _optional_ | If specified, if the entity colliding with the border, and the entity with this power fulfil the condition, the colliding entity can walk through the border.
`red` | [Float](../data_types/float.md) | 0.1254902 | The red value of the border.
`green` | [Float](../data_types/float.md) | 0.627451 | The green value of the border.
`blue` | [Float](../data_types/float.md) | 1.0 | The blue value of the border.
`alpha` | [Float](../data_types/float.md) | 0.5 | The alpha (transparency) value of the border.
`scroll_texture` | [Boolean](../data_types/boolean.md) | true | Defines whether the border scrolls like the vanila border.
`size` | [Double](../data_types/double.md) | 6.0 | The distance to one side of the border from the center.

### Example
```json
{
  "type": "ra_additions:border",
  "size": 12,
  "red": 1,
  "green": 1,
  "blue": 1,
  "alpha": 0.5,
  "scroll_texture": false,
  "border_texture": "minecraft:textures/block/dirt.png",
  "entity_condition": {
    "type": "origins:creative_flying"
  }
}
```
This example will create a border the entity will be able to walk through, but will be unable to fly through.