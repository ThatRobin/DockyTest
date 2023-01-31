# Item Use
[Power Type](../power_types.md)

This power uses the existing item interaction system in Minecraft to execute actions. which means that when used, the actions won't happen if something of higher priority occurs (for example opening a chest).

Type ID: `ra_additions:item_use`
### Fields
Field | Type | Default | Description
------|------|---------|-------------
`cooldown` | [Int](../data_types/int.md) | 0 | Sets a cooldown on the item (Similar to ender pearl cooldowns).
`entity_action` | [Entity Action](../data_types/entity_action.md) | _optional_ | The entity action to be executed on the player if specified.
`item_condition` | [Item Condition](../data_types/item_condition.md) | _optional_ | If specified, only execute the action if the item condition is fulfilled.
`item_action` | [Item Action](../data_types/item_action.md) | _optional_ | The item action to be executed if specified.

### Example
```json
{
    "type": "ra_additions:item_use",
    "cooldown": 20,
    "item_action": {
        "type": "apoli:damage",
        "amount": 1
    }
}```
INSERT DESCRIPTION HERE
