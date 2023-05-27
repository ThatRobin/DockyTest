# Flee Entity
[Task Types](../task_types.md)

Type ID: `ra_additions:flee_entity
### Fields
 | Field | Type | Default | Description | 
|---|---|---|---|
 | `priority` | [Array](../data_types/array.md) of [Int](../data_types/int.md) | _optional_ | null | 
 | `distance` | [Array](../data_types/array.md) of [Float](../data_types/float.md) | _optional_ | null | 
 | `slow_speed` | [Array](../data_types/array.md) of [Double](../data_types/double.md) | _optional_ | null | 
 | `fast_speed` | [Array](../data_types/array.md) of [Double](../data_types/double.md) | _optional_ | null | 
 | `bientity_condition` | [Array](../data_types/array.md) of [Bientity Condition](../bientity_condition_types.md) | _optional_ | null | 

### Example
```json
{
  "type": "ra_additions:flee_entity",
  "priority": 0,
  "distance": 8,
  "slow_speed": 1.6,
  "fast_speed": 1.4,
  "bientity_condition": {
    "type": "apoli:target_condition",
    "condition": {
      "type": "apoli:entity_type",
      "entity_type": "minecraft:creeper"
    }
  }
}
```

