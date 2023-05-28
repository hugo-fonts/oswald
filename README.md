# Oswald font for Hugo

This module provides CSS and web fonts for [Oswald](https://github.com/googlefonts/OswaldFont).

By default, only Latin and Latin Extended character sets are included.
Optionally, Cyrillic and Vietnamese are available in addition to Latin.

To use, import this module from your `config.toml`.

## Latin only

```toml
[module]
[[module.imports]]
path = "github.com/hugo-fonts/oswald"
```

To enable the font in a template, use `/css/oswald-latin.css`.

## Cyrillic
```toml
[module]
[[module.imports]]
path = "github.com/hugo-fonts/oswald/cyrillic"
```

To enable the font in a template, use `/css/oswald-cyrillic.css`.

## Vietnamese
```toml
[module]
[[module.imports]]
path = "github.com/hugo-fonts/oswald/vietnamese"
```

To enable the font in a template, use `/css/oswald-vietnamese.css`.
