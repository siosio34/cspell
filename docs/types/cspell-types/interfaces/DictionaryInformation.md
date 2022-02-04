[@cspell/cspell-types](../README.md) / [Exports](../modules.md) / DictionaryInformation

# Interface: DictionaryInformation

Use by dictionary authors to help improve the quality of suggestions
given from the dictionary.

Added with `v5.16.0`.

## Table of contents

### Properties

- [accents](DictionaryInformation.md#accents)
- [alphabet](DictionaryInformation.md#alphabet)
- [costs](DictionaryInformation.md#costs)
- [hunspellInformation](DictionaryInformation.md#hunspellinformation)
- [locale](DictionaryInformation.md#locale)
- [suggestionEditCosts](DictionaryInformation.md#suggestioneditcosts)

## Properties

### accents

• `Optional` **accents**: `string` \| [`CharacterSetCosts`](CharacterSetCosts.md)[]

The accent characters

**`default`** "\u0300-\u0341"

#### Defined in

[DictionaryInformation.ts:26](https://github.com/streetsidesoftware/cspell/blob/d52d68a/packages/cspell-types/src/DictionaryInformation.ts#L26)

___

### alphabet

• `Optional` **alphabet**: `string` \| [`CharacterSetCosts`](CharacterSetCosts.md)[]

The alphabet to use.

**`default`** "a-zA-Z"

#### Defined in

[DictionaryInformation.ts:20](https://github.com/streetsidesoftware/cspell/blob/d52d68a/packages/cspell-types/src/DictionaryInformation.ts#L20)

___

### costs

• `Optional` **costs**: [`EditCosts`](EditCosts.md)

Define edit costs.

#### Defined in

[DictionaryInformation.ts:31](https://github.com/streetsidesoftware/cspell/blob/d52d68a/packages/cspell-types/src/DictionaryInformation.ts#L31)

___

### hunspellInformation

• `Optional` **hunspellInformation**: `HunspellInformation`

Used by dictionary authors

#### Defined in

[DictionaryInformation.ts:42](https://github.com/streetsidesoftware/cspell/blob/d52d68a/packages/cspell-types/src/DictionaryInformation.ts#L42)

___

### locale

• `Optional` **locale**: `string`

The locale of the dictionary.
Example: `nl,nl-be`

#### Defined in

[DictionaryInformation.ts:14](https://github.com/streetsidesoftware/cspell/blob/d52d68a/packages/cspell-types/src/DictionaryInformation.ts#L14)

___

### suggestionEditCosts

• `Optional` **suggestionEditCosts**: [`SuggestionCostsDefs`](../modules.md#suggestioncostsdefs)

Used in making suggestions. The lower the value, the more likely the suggestion
will be near the top of the suggestion list.

#### Defined in

[DictionaryInformation.ts:37](https://github.com/streetsidesoftware/cspell/blob/d52d68a/packages/cspell-types/src/DictionaryInformation.ts#L37)