# Boss Bar Hud Overlay
[Data Type](../data_types.md)

An [Object](object.md) used to define how a boss bar's overlay should be rendered.
## Fields

 | Field | Type | Default | Description | 
|---|---|---|---|
 | should_render | [Backwards Compatible Key](null.md) | _optional_ | Whether the bar should be visible or not. | 
 | bar_index | [Backwards Compatible Key](null.md) | _optional_ | The indexed position of the bar on the sprite to use. Please note that indexes start at 0. | 
 | priority | [Backwards Compatible Key](null.md) | _optional_ | The order in which the bar appears on the screen. | 
 | sprite_location | [Backwards Compatible Key](null.md) | _optional_ | The path to the file in the assets which contains what the bar looks like. | 
 | null | null | null | null | 
 | null | null | null | null | 

## Example
```json
{
  "sprite_location": "textures/gui/bars.png",
  "bar_index": 1,
  "should_render": true,
  "condition": {
    "type": "apoli:exposed_to_sun"
  }
}
```

