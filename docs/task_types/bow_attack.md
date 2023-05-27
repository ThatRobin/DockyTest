# Bow Attack
[Task Types](../task_types.md)



Type ID: `ra_additions:bow_attack`
### Fields
 | Field | Type | Default | Description | 
|---|---|---|---|
 | `priority` | [Array](../data_types/array.md) of [Int](../data_types/int.md) | _optional_ | null | 
 | `speed` | [Array](../data_types/array.md) of [Double](../data_types/double.md) | _optional_ | null | 
 | `attack_interval` | [Array](../data_types/array.md) of [Int](../data_types/int.md) | _optional_ | null | 
 | `range` | [Array](../data_types/array.md) of [Float](../data_types/float.md) | _optional_ | null | 
 | `bientity_condition` | [Array](../data_types/array.md) of [Bientity Condition](../bientity_condition_types.md) | _optional_ | null | 

### Example
```json
{
  "type": "ra_additions:bow_attack",
  "priority": 0,
  "speed": 1,
  "attack_interval": 20,
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

