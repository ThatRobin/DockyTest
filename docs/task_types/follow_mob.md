# Follow Mob
[Task Types](../task_types.md)



Type ID: `ra_additions:follow_mob`
### Fields
 | Field | Type | Default | Description | 
|---|---|---|---|
 | `priority` | [Int](../data_types/int.md) | _optional_ | null | 
 | `speed` | [Double](../data_types/double.md) | _optional_ | null | 
 | `can_be_scared` | [Boolean](../data_types/boolean.md) | _optional_ | null | 
 | `bientity_condition` | [Bientity Condition](../bientity_condition_types.md) | _optional_ | null | 

### Example
```json
{
  "type": "ra_additions:follow_mob",
  "priority": 0,
  "speed": 1,
  "can_be_scared": false,
  "bientity_condition": {
    "type": "apoli:target_condition",
    "condition": {
      "type": "apoli:entity_type",
      "entity_type": "minecraft:creeper"
    }
  }
}
```

