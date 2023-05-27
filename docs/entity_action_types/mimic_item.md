# Mimic Item
[Entity Action Types](../entity_action_types.md)
Executes a given Item Stack's use ability.
Type ID: `ra_additions:mimic_item
### Fields
 | Field | Type | Default | Description | 
|---|---|---|---|
 | `item_stack` | [Array](../data_types/array.md) of [Item Stack](../data_types/item_stack.md) | _optional_ | The stack to be used for the action | 
 | `hand` | [Array](../data_types/array.md) of [Hand](../data_types/hand.md) | _optional_ | The hand for the action to use | 

### Example
```json
{
  "type": "ra_additions:mimic_item",
  "item_stack": {
    "item": "minecraft:shield"
  }
}
```

