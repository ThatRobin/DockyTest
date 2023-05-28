# Active Target
[Task Types](../task_types.md)

1

Type ID: `ra_additions:active_target`
### Fields
 | Field | Type | Default | Description | 
|---|---|---|---|
 | `priority` | [Int](../data_types/int.md) | _optional_ | null | 
 | `reciprocal_chance` | [Int](../data_types/int.md) | _optional_ | null | 
 | `check_visibility` | [Boolean](../data_types/boolean.md) | _optional_ | null | 
 | `check_can_navigate` | [Boolean](../data_types/boolean.md) | _optional_ | null | 
 | `bientity_condition` | [Bientity Condition](../bientity_condition_types.md) | _optional_ | null | 

### Example
```json
{
  "type": "ra_additions:active_target",
  "priority": 0,
  "reciprocal_chance": 10,
  "check_visibility": true,
  "check_can_navigate": false,
  "bientity_condition": {
    "type": "apoli:attacker"
  }
}
```

