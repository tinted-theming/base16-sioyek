# Base16-sioyek

> See the [Tinted theming repository](https://github.com/tinted-theming/home) for more information.
> This theme was built with [Tinted Builder Rust](https://github.com/tinted-theming/tinted-builder-rust).

[Base16](https://github.com/tinted-theming/home/blob/main/styling.md) color schemes for the [sioyek](https://github.com/ahrm/sioyek) pdf reader.

<div align="center"><img width=600 src="./assets/screenshot.png" alt="Screenshot of a figure within a pdf file, with the gruvbox theme"><p>Figure 1: Sioyek with gruvbox hard and custom colors enabled</p></div>

## Installation

Clone and copy the color scheme's config file to `$XDG_CONFIG_HOME/sioyek/prefs_user.config`.

```sh
git clone git@github.com:tinted-theming/base16-sioyek.git
cp base16-sioyek/colors/base16-gruvbox-dark-hard.config ~/.config/sioyek/prefs_user.config
```

To include the colors while keeping your own `prefs_user.config` file, save the theme file to a different file and source it. For example, to `~/.config/sioyek/colors.config` and add the following to your `prefs_user.config` file:

```config
source ~/.config/sioyek/colors.config
```
