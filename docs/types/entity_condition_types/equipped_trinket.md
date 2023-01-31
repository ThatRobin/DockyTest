# Equipped Trinket
[Entity Condition Type](../entity_condition_types.md)

Checks all the players trinket slots with an [Item Condition](https://origins.readthedocs.io/en/latest/types/item_condition_types/).

Type ID: `ra_additions:equipped_trinket`
### Fields
Field | Type | Default | Description
------|------|---------|-------------
`item_condition` | [Item Condition](../data_types/item_condition.md) | _optional_ | The items that are searched for in the trinket slots.

### Example
```json
{
  "type": "ra_additions:equipped_trinket",
  "item_condition": {
    "type": "apoli:ingredient",
    "ingredient": {
      "item": "minecraft:emerald"
    }
  }
}
```
This example will check if the entity has an emerald equipped in any of their trinkets slots.
