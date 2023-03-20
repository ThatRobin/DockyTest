# Crossbow Attack
[Task Types](../task_types_types.md)



Type ID: `ra_additions:crossbow_attack`
### Fields
Field | Type | Default | Description
------|------|---------|-------------
`priority` | [Int](../data_types/int.md) | 0 | null
`speed` | [Double](../data_types/double.md) | 1.0 | null
`range` | [Float](../data_types/float.md) | 15.0 | null
`bientity_condition` | [Bientity Condition](../bientity_condition_types.md) | _optional_ | null

### Example
```json
{
  "type": "ra_additions:bow_attack",
  "priority": 0,
  "speed": 1,
  "range": 15,
  "bientity_condition": {
    "type": "apoli:target_condition",
    "condition": {
      "type": "apoli:entity_type",
      "entity_type": "minecraft:creeper"
    }
  }
}
```
