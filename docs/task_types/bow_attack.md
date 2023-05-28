# Bow Attack
[Task Types](../task_types.md)



Type ID: `ra_additions:bow_attack`
### Fields
 | Field | Type | Default | Description | 
|---|---|---|---|
 | `priority` | [Int](../data_types/int.md) | _optional_ | null | 
 | `speed` | [Double](../data_types/double.md) | _optional_ | null | 
 | `attack_interval` | [Int](../data_types/int.md) | _optional_ | null | 
 | `range` | [Float](../data_types/float.md) | _optional_ | null | 
 | `bientity_condition` | [Bientity Condition](../bientity_condition_types.md) | _optional_ | null | 

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

