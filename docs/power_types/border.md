# Border
[Power Types](../power_types.md)

Creates a border around the entity with this power. Only entities that fulfil the conditions may pass through it.

Type ID: `ra_additions:border`
### Fields
 | Field | Type | Default | Description | 
|---|---|---|---|
 | `border_texture` | [Identifier](../data_types/identifier.md) | _optional_ | The texture used on the border. | 
 | `entity_condition` | [Entity Condition](../entity_condition_types.md) | _optional_ | If specified, if the entity colliding with the border fulfils the condition, it can walk through the border. | 
 | `bientity_condition` | [Bientity Condition](../bientity_condition_types.md) | _optional_ | If specified, if the entity colliding with the border, and the entity with this power fulfil the condition, the colliding entity can walk through the border. | 
 | `red` | [Float](../data_types/float.md) | _optional_ | The red value of the border. | 
 | `green` | [Float](../data_types/float.md) | _optional_ | The green value of the border. | 
 | `blue` | [Float](../data_types/float.md) | _optional_ | The blue value of the border. | 
 | `alpha` | [Float](../data_types/float.md) | _optional_ | The alpha (transparency) value of the border. | 
 | `scroll_texture` | [Boolean](../data_types/boolean.md) | _optional_ | Defines whether the border scrolls like the vanila border. | 
 | `size` | [Double](../data_types/double.md) | _optional_ | The distance to one side of the border from the center. | 

### Example
```json
{
  "type": "ra_additions:border",
  "size": 12,
  "red": 1,
  "green": 1,
  "blue": 1,
  "alpha": 1,
  "scroll_texture": false,
  "entity_condition": {
    "type": "origins:creative_flying"
  }
}
```
This example will create a border the entity will be able to walk through, but will be unable to fly through.
