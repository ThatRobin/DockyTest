# Has Item In Recipe
[Block Condition Types](../block_condition_types_types.md)

Checks if the recipe that outputs this block, has an item in it that matches this condition.

Type ID: `ra_additions:has_item_in_recipe`
### Fields
Field | Type | Default | Description
------|------|---------|-------------
`recipe_type` | [Recipe Type](../data_types/recipe_type.md) | crafting | 
`item_condition` | [Item Condition](../item_condition_types.md) | _optional_ | 

### Example
```json
{
  "type": "ra_additions:has_item_in_recipe",
  "recipe_type": "smelting",
  "item_condition": {
    "type": "ra_additions:is_block"
  }
}
```
This example will check if the smelting recipe to create this block, is also a block