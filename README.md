# Reticle Graphite

An Omarchy theme that keeps Reticle's green text on a #1c1c1c graphite
background instead of pure black, for dark mode in a bright room.

## Install

```sh
omarchy theme install https://github.com/solforged/omarchy-reticle-graphite-theme.git
```

The repository name makes Omarchy install it as `reticle-graphite`.

## Contents

`colors.toml` is the palette source of truth. Current Omarchy releases
regenerate terminal adapters from it when installing a Git-hosted theme; the
repository also keeps an icon preference and the original Ghostty, Alacritty, Foot, and
Kitty adapters.

`neovim.lua` selects the `reticle-graphite` colorscheme, which comes from the
[Reticle](https://github.com/solforged/reticle) Neovim port. Without that port,
LazyVim falls back to its default colorscheme.

## License

The palette is adapted from the
[USGC themes](https://github.com/usgraphics/usgc-themes) by U.S. Graphics
Company, used under the BSD 3-Clause License in [LICENSE](LICENSE).
