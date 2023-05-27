# Tempt
[Task Types](../task_types.md)



Type ID: `ra_additions:tempt`
### Fields
 | Field | Type | Default | Description | 
|---|---|---|---|
 | `priority` | [Array](../data_types/array.md) of [Int](../data_types/int.md) | _optional_ | null | 
 | `speed` | [Array](../data_types/array.md) of [Double](../data_types/double.md) | _optional_ | null | 
 | `can_be_scared` | [Array](../data_types/array.md) of [Boolean](../data_types/boolean.md) | _optional_ | null | 
 | `bientity_condition` | [Array](../data_types/array.md) of [Bientity Condition](../bientity_condition_types.md) | _optional_ | null | 

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

