# cosy-termcolors.kak

Colorscheme for Kakoune editor that uses 16 base terminal colors. Useful to easily match text editor look with other
CLI utilities. Good terminal colorscheme is recommended.

This colorscheme assumes that "bright" color variants are defined to have maximum contrast against the background
(darker for light themes, lighter for dark themes). Black is used as a background color and white as a foreground.

## Installation

### Via [plug.kak](https://github.com/andreyorst/plug.kak)

```kak
plug "Anfid/cosy-termcolors.kak" theme config %{
    colorscheme cosy-termcolors
}
```

### Without plugin manager

Place a symbolic link or copy `cosy-termcolors.kak` to your `colors` folder at Kakoune configuration folder.
