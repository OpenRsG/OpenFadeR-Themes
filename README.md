# OpenFadeR-Themes

Themes for [OpenFadeR](https://github.com/OpenRsG/OpenFadeR). The app's built-in themes are Catppuccin Mocha (the default)
and Catppuccin Latte; this repository holds the others.

| Theme | Base | |
|---|---|---|
| Catppuccin Frappé, Macchiato | dark | the other two Catppuccin flavours |
| Rek, Rek Light | dark / light | neutral greys, blue accents, green play, amber cues |
| So Pro | dark | near-black greys, bright blue accent, white platter, 4 × 2 coloured pads, vertical 2-deck layout |
| Dracula, Nord, Gruvbox Dark, Tokyo Night | dark | the well-known palettes |
| Ocean, High Contrast | dark | small examples that set only a few tokens |

## Install

In the app: PREFERENCES > THEMES > GET THEMES lists every theme of this repository (it is there by default); one click
installs a theme and it shows in the gallery. Or copy the `.json` files you want into `~/.config/openfader/extension/skin/`,
drop one on the app window, or point the app at this checkout:

```sh
OPENFADER_SKINS=/path/to/OpenFadeR-Themes openfader
```

Then pick the theme in PREFERENCES > THEMES. A theme is one JSON file; the token list and format are in the core
repository's `docs/skins.md`.

## License

AGPL-3.0, see `LICENSE`.
