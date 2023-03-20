# Melee Attack
[Task Types](../task_types_types.md)



Type ID: `ra_additions:melee_attack`
### Fields
Field | Type | Default | Description
------|------|---------|-------------
`priority` | [Int](../data_types/int.md) | 0 | null
`bientity_condition` | [Bientity Condition](../bientity_condition_types.md) | _optional_ | null

### Example
```json
{
  "type": "ra_additions:melee_attack",
  "priority": 0,
  "bientity_condition": {
    "type": "apoli:target_condition",
    "condition": {
      "type": "apoli:entity_type",
      "entity_type": "minecraft:creeper"
    }
  }
}
```
