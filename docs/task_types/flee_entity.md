# Flee Entity
[Task Types](../task_types.md)



Type ID: `ra_additions:flee_entity`
### Fields
 | Field | Type | Default | Description | 
|---|---|---|---|
 | `priority` | [Int](../data_types/int.md) | _optional_ | null | 
 | `distance` | [Float](../data_types/float.md) | _optional_ | null | 
 | `slow_speed` | [Double](../data_types/double.md) | _optional_ | null | 
 | `fast_speed` | [Double](../data_types/double.md) | _optional_ | null | 
 | `bientity_condition` | [Bientity Condition](../bientity_condition_types.md) | _optional_ | null | 

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

