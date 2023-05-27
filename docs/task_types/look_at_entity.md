# Look At Entity
[Task Types](../task_types.md)

Type ID: `ra_additions:look_at_entity
### Fields
 | Field | Type | Default | Description | 
|---|---|---|---|
 | `priority` | [Array](../data_types/array.md) of [Int](../data_types/int.md) | _optional_ | null | 
 | `range` | [Array](../data_types/array.md) of [Float](../data_types/float.md) | _optional_ | null | 
 | `bientity_condition` | [Array](../data_types/array.md) of [Bientity Condition](../bientity_condition_types.md) | _optional_ | null | 

### Example
```json
{
  "type": "ra_additions:melee_attack",
  "priority": 0,
  "range": 6,
  "bientity_condition": {
    "type": "apoli:target_condition",
    "condition": {
      "type": "apoli:entity_type",
      "entity_type": "minecraft:creeper"
    }
  }
}
```

