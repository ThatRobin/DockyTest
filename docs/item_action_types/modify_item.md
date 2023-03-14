# Modify item
[Item action types Type](../item_action_types_types.md)

Applies an item modifier to the item stack with a player fulfilling the "this" criteria.

Type ID: `ra_additions:modify_item`
### Fields
Field | Type | Default | Description
------|------|---------|-------------
`modifier` | [Identifier](../data_types/identifier.md) | _optional_ | The Identifier of an item modifier.

### Example
```json
{
  "type": "ra_additions:modify_item",
  "modifier": "test_pack:stuff"
}
```
This example will apply the `test_pack:stuff` item modifier to the item.