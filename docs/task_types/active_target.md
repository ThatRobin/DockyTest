# Active Target
[Task Types](../task_types_types.md)

1

Type ID: `ra_additions:active_target`
### Fields
Field | Type | Default | Description
------|------|---------|-------------
`priority` | [Int](../data_types/int.md) | 0 | null
`reciprocal_chance` | [Int](../data_types/int.md) | 10 | null
`check_visibility` | [Boolean](../data_types/boolean.md) | true | null
`check_can_navigate` | [Boolean](../data_types/boolean.md) | false | null
`bientity_condition` | [Bientity Condition](../bientity_condition_types.md) | _optional_ | null

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
