# Execute action
[Bientity action types](../bientity_action_types_types.md)

Executes a bi-entity action that is stored in a file.

Type ID: `ra_additions:execute_action`
### Fields
Field | Type | Default | Description
------|------|---------|-------------
`bientity_action` | [String](../data_types/string.md) | _optional_ | The Identifier of the tag or action file to be executed

### Example
```json
{
  "type": "ra_additions:execute_action",
  "bientity_action": "test_pack:attack_example"
}
```
This example will run the `test_pack:attack_example` bi-entity action.