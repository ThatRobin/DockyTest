# Item Use
[Power Type](../power_types.md)
This power uses the existing item interaction system in Minecraft to execute actions. which means that when used, the actions won't happen if something of higher priority occurs (for example opening a chest).
Type ID: `ra_additions:item_use`
### Fields
Field | Type | Default | Description
------|------|---------|-------------
`cooldown` | [Int](../data_types/int.md) | 0 | null
`entity_action` | [Entity Action](../data_types/entity_action.md) | _optional_ | null
`item_condition` | [Item Condition](../data_types/item_condition.md) | _optional_ | null
`item_action` | [Item Action](../data_types/item_action.md) | _optional_ | null
`condition` | [Entity Condition](../data_types/entity_condition.md) | _optional_ | null

