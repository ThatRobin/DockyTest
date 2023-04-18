# Universal Powers
In order to use the universal power system. you make your power files as you would in Origins. And then make the directories `/data/<namespace>/universal_powers/` and create a JSON file in there (it can be named anything)
Then, in this file, you enter your powers, and entities.

 | Fields | Type | Default | Description | 
|---|---|---|---|
 | `powers` | [Array](data_types/array.md) of [Identifiers](data_types/identifier.md) | _optional_ | The namespace and IDs of the powers you want to give to all entities. | 
 | `entity_entry` | [Entity Entry](data_types/entity_entry.md) | _optional_ | An object that accepts either an `entity` or a `tag` [Identifier](data_types/identifier.md). Cannot be both. | 

### Examples
```json
{
  "powers": [
    "ra_additions:no_wool"
  ],
  "entity_entry": {
    "entity": "minecraft:sheep"
  }
}
```
This example would apply the power `ra_additions:no_wool` to all sheep.
```json
{
  "powers": [
    "ra_additions:ignore_water"
  ],
  "entity_entry": {
    "tag": "minecraft:skeletons"
  }
}
```
This example would apply the power `ra_additions:ignore_water` to all entities in the `minecraft:skeletons` Entity Type tag.
