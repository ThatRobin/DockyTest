# Resource Percentage
[Entity Condition Type](../entity_condition_types.md)

Checks the percentage of a resource.

Type ID: `ra_additions:resource_percentage`
### Fields
Field | Type | Default | Description
------|------|---------|-------------
`resource` | [Power Type](../data_types/power_type.md) | _optional_ | The Identifier of the power type that defines the resource which exists on the player.
`comparison` | [Comparison](../data_types/comparison.md) | EQUAL | How the value of the power that will be evaluated should be compared to the specified value.
`percentage` | [Int](../data_types/int.md) | 50 | The percentage value to compare the value of the power that will be evaluated to. `(e.g 50%)`

### Example
```json
{
    "type": "ra_additions:resource_percentage",
    "resource": "example_pack:magic_resource",
    "comparison": ">=",
    "percentage": 75
}```
INSERT DESCRIPTION HERE
