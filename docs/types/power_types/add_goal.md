# Add Goal
[Power Type](../power_types.md)
Adds a custom goal (from `data/{namespace}/goals/`) to the entity with this power.
Type ID: `ra_additions:add_goal`
### Fields
Field | Type | Default | Description
------|------|---------|-------------
`goal` | [Identifier](../data_types/identifier.md) | _optional_ | The goal to add to the mob.
`goals` | [Identifiers](../data_types/identifiers.md) | [] | The goals to add to the mob.
`condition` | [Entity Condition](../data_types/entity_condition.md) | _optional_ | null

### Example
```json
{
    "type": "ra_additions:add_goal",
    "goal": "example:stuff"
}```
INSERT DESCRIPTION HERE
