# Toggle
[Power Types](../power_types.md)
A custom version of Apoli's [Toggle (Power Type)](https://origins.readthedocs.io/en/latest/types/power_types/toggle/)
Type ID: `ra_additions:toggle
### Fields
 | Field | Type | Default | Description | 
|---|---|---|---|
 | `active_by_default` | [Array](../data_types/array.md) of [Boolean](../data_types/boolean.md) | _optional_ | Whether this power starts in the on or off state. | 
 | `retain_state` | [Array](../data_types/array.md) of [Boolean](../data_types/boolean.md) | _optional_ | Whether this power switches back to default if the condition is no longer met. | 
 | `toggle_on_action` | [Array](../data_types/array.md) of [Entity Action](../entity_action_types.md) | _optional_ | The entity action to be executed when the power is toggled on. | 
 | `toggle_off_action` | [Array](../data_types/array.md) of [Entity Action](../entity_action_types.md) | _optional_ | The entity action to be executed when the power is toggled off. | 
 | `key` | [Array](../data_types/array.md) of [Backwards Compatible Key](https://origins.readthedocs.io/en/latest/types/data_types/key/) | _optional_ | Which active key this power should respond to. | 

### Example
```json
{
  "type": "ra_additions:toggle",
  "active_by_default": false,
  "key": {
    "key": "key.use"
  }
}
```
This example will provide a switch that is not active by default, and can be toggled with the `key.use` keybind.
