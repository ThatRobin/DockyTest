# Item Use
[Power Types](../power_types.md)

This power uses the existing item interaction system in Minecraft to execute actions. which means that when used, the actions won't happen if something of higher priority occurs (for example opening a chest).

Type ID: `ra_additions:item_use`
### Fields
 | Field | Type | Default | Description | 
|---|---|---|---|
 | `cooldown` | [Array](../data_types/array.md) of [Int](../data_types/int.md) | _optional_ | Sets a cooldown on the item (Similar to ender pearl cooldowns). | 
 | `entity_action` | [Array](../data_types/array.md) of [Entity Action](../entity_action_types.md) | _optional_ | The entity action to be executed on the player if specified. | 
 | `item_condition` | [Array](../data_types/array.md) of [Item Condition](../item_condition_types.md) | _optional_ | If specified, only execute the action if the item condition is fulfilled. | 
 | `item_action` | [Array](../data_types/array.md) of [Item Action](../item_action_types.md) | _optional_ | The item action to be executed if specified. | 

### Example
```json
{
  "type": "ra_additions:item_use",
  "cooldown": 20,
  "item_action": {
    "type": "apoli:damage",
    "amount": 1
  }
}
```
This example will make it so that you can use any item, which lowers it's durability by 1, and put that item on cooldown for 20 seconds.
