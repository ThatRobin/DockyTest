# Entity Entry
[Data Type](../data_types.md)

_Either_: an [Object](object.md) specifying a registered entity or entity tag.

_Or_: an [Array](array.md) of [Objects](object.md) specifying a registered item or item tag.

## Fields

 | Field | Type | Default | Description | 
|---|---|---|---|
 | entity | [Backwards Compatible Key](null.md) | _optional_ | ID of a registered entity. | 
 | tag | [Backwards Compatible Key](null.md) | _optional_ | ID of an entity tag. Will be ignored if `entity` is set. | 

## Example
```json
{
  "tag": "minecraft:skeletons"
}
```

