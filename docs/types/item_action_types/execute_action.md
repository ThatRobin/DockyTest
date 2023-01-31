# Execute Action
[Item Action Type](../item_action_types.md)
Executes an item action that is stored in a file.
Type ID: `ra_additions:execute_action`
### Fields
Field | Type | Default | Description
------|------|---------|-------------
`item_action` | [String](../data_types/string.md) | _optional_ | The Identifier of the tag or action file to be executed

### Example
```json
{
    "type": "ra_additions:execute_action",
    "item_action": "example_pack:modify_item_example"
}```
INSERT DESCRIPTION HERE
