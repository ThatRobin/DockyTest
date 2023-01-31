# Execute Action
[Entity Action Type](../entity_action_types.md)
Executes an entity action that is stored in a file.
Type ID: `ra_additions:execute_action`
### Fields
Field | Type | Default | Description
------|------|---------|-------------
`entity_action` | [String](../data_types/string.md) | _optional_ | The Identifier of the tag or action file to be executed

### Example
```json
{
    "type": "ra_additions:execute_action",
    "entity_action": "example_pack:open_choice_screen_example"
}```
INSERT DESCRIPTION HERE
