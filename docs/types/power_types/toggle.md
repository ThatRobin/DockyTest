# Toggle
[Power Type](../power_types.md)

A custom version of Apoli's [Toggle (Power Type)](https://origins.readthedocs.io/en/latest/types/power_types/toggle/)

Type ID: `ra_additions:toggle`
### Fields
Field | Type | Default | Description
------|------|---------|-------------
`active_by_default` | [Boolean](../data_types/boolean.md) | true | Whether this power starts in the on or off state.
`retain_state` | [Boolean](../data_types/boolean.md) | true | Whether this power switches back to default if the condition is no longer met.
`toggle_on_action` | [Entity Action](../data_types/entity_action.md) | _optional_ | The entity action to be executed when the power is toggled on.
`toggle_off_action` | [Entity Action](../data_types/entity_action.md) | _optional_ | The entity action to be executed when the power is toggled off.
`key` | [Backwards Compatible Key](../data_types/backwards_compatible_key.md) | io.github.apace100.apoli.power.Active$Key@642405e | Which active key this power should respond to.

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
