# Attack
[Bientity Action Type](../bientity_action_types.md)
The actor entity will damage the target enemy as if they had just been hit with the weapon in the actors hand.
Type ID: `ra_additions:attack`
### Fields
Field | Type | Default | Description
------|------|---------|-------------
`source` | [Damage Source](../data_types/damage_source.md) | _optional_ | The damage source to be used. Controls e.g. the death message, invulnerabilities (e.g. towards fire), or whether armor is taken into account.
`allow_enchants` | [Boolean](../data_types/boolean.md) | false | Should enchantments be taken into account in the attack.
`allow_weapons` | [Boolean](../data_types/boolean.md) | false | Should weapons/tools be taken into account in the attack.
`allow_effects` | [Boolean](../data_types/boolean.md) | false | Should effects be taken into account in the attack.
`allow_attributes` | [Boolean](../data_types/boolean.md) | false | Should attributes be taken into account in the attack.
`inverted` | [Boolean](../data_types/boolean.md) | false | null

### Example
```json
{
    "type": "ra_additions:attack",
    "allow_enchants": true,
    "allow_weapons": true,
    "allow_effects": true,
    "allow_attributes": true,
    "source": {
        "name": "player",
        "bypasses_armor": true
    }
}```
INSERT DESCRIPTION HERE
