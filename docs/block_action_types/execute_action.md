# Execute action
[Block action types Type](../block_action_types_types.md)

Executes a block action that is stored in a file.

Type ID: `ra_additions:execute_action`
### Fields
Field | Type | Default | Description
------|------|---------|-------------
`block_action` | [String](../data_types/string.md) | _optional_ | The Identifier of the tag or action file to be executed

### Example
```json
{
  "type": "ra_additions:execute_action",
  "block_action": "test_pack:test_action"
}
```
This example will run the `test_pack:test_action` block action.