# Attack
[Task Types](../task_types.md)

Type ID: `ra_additions:attack
### Fields
 | Field | Type | Default | Description | 
|---|---|---|---|
 | `priority` | [Array](../data_types/array.md) of [Int](../data_types/int.md) | _optional_ | null | 
 | `bientity_condition` | [Array](../data_types/array.md) of [Bientity Condition](../bientity_condition_types.md) | _optional_ | null | 

### Example
```json
{
  "type": "ra_additions:attack",
  "priority": 0,
  "bientity_condition": {
    "type": "apoli:attacker"
  }
}
```

