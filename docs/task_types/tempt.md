# Tempt
[Task Types](../task_types_types.md)



Type ID: `ra_additions:tempt`
### Fields
Field | Type | Default | Description
------|------|---------|-------------
`priority` | [Int](../data_types/int.md) | 0 | null
`speed` | [Double](../data_types/double.md) | 1.2 | null
`can_be_scared` | [Boolean](../data_types/boolean.md) | true | null
`bientity_condition` | [Bientity Condition](../bientity_condition_types.md) | _optional_ | null

### Example
```json
{
  "type": "ra_additions:tempt",
  "priority": 0,
  "speed": 1.2,
  "can_be_scared": true,
  "bientity_condition": {
    "type": "apoli:target_condition",
    "condition": {
      "type": "apoli:entity_type",
      "entity_type": "minecraft:creeper"
    }
  }
}
```
