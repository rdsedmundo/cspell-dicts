# Cspell Russian Dictionary (Deprecated)

_Use:_ [cspell-dict-ru_ru - npm](https://www.npmjs.com/package/cspell-dict-ru_ru)

Russian dictionary for cspell.

This is a pre-built dictionary for use with cspell.

## Installation

Global Install and add to cspell global settings.

```sh
npm install -g cspell-dict-russian
cspell-dict-russian-link
```

## Uninstall from cspell

```sh
cspell-dict-russian-unlink
```

## Manual Installation

The `cspell-ext.json` file in this package should be added to the import section in your cspell.json file.

```javascript
{
    // …
    "import": ["<path to node_modules>/cspell-dict-russian/cspell-ext.json"],
    // …
}
```

## Building

Building is only necessary if you want to modify the contents of the dictionary. Note: Building will take a few minutes for large files.

```sh
npm run build
```

## Resources

The Hunspell source for this dictionary can be found:

- https://github.com/titoBouzout/Dictionaries

## License

MIT

> Some packages may have other licenses included.
