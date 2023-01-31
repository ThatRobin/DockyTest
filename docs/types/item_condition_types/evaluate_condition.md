# Evaluate Condition
[Item Condition Type](../item_condition_types.md)
Evaluates an item condition that is stored in a file.
Type ID: `ra_additions:evaluate_condition`
### Fields
Field | Type | Default | Description
------|------|---------|-------------
`item_condition` | [String](../data_types/string.md) | _optional_ | The Identifier of the tag or condition file to be evaluated

### Example
```json
{
    "type": "ra_additions:evaluate_condition",
    "item_condition": "example_pack:test_condition"
}```
INSERT DESCRIPTION HERE
