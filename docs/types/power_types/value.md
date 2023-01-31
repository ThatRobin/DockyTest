# Value
[Power Type](../power_types.md)

Defines a value for the player. Essentially identical to a [Resource Bar](https://origins.readthedocs.io/en/latest/types/power_types/resource/) but displays as number in a string.

Type ID: `ra_additions:value`
### Fields
Field | Type | Default | Description
------|------|---------|-------------
`min` | [Int](../data_types/int.md) | -2147483648 | The minimum value of the power.
`max` | [Int](../data_types/int.md) | 2147483647 | The maximum value of the power.
`x` | [Int](../data_types/int.md) | 0 | The X co-ordinate that the string will appear at.
`y` | [Int](../data_types/int.md) | 0 | The Y co-ordinate that the string will appear at.
`value_key` | [String](../data_types/string.md) | _optional_ | The string that will contain the value
`start_value` | [Int](../data_types/int.md) | _optional_ | The value of the power when the entity first receives it. If not set, this will be set to the value of the min integer field.

### Example
```json
{
  "type": "ra_additions:value",
  "x": 70,
  "y": 70,
  "value_key": "You have %s value"
}```
This example is a value, which creates a string of text that says `you have X value` where X is the internal value of the power.
