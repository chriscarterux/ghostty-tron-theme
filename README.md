# Tron Theme for Ghostty

A neon-inspired terminal theme for [Ghostty](https://ghostty.org/) based on the iconic TRON aesthetic. Features vibrant cyan and neon colors optimized for readability during development work.

![Theme Preview](preview.png)

## Features

- **Pure black background** (`#000000`) for deep contrast
- **Bright cyan foreground** (`#E6F8FF`) for excellent readability
- **Neon cyan cursor** (`#00EFFF`) that stands out
- **Full ANSI color palette** with bright, vivid colors
- Optimized for both light and dark environments

## Installation

### Method 1: Direct Theme File

1. Copy `tron.conf` to your Ghostty themes directory:
   ```bash
   mkdir -p ~/.config/ghostty/themes
   cp tron.conf ~/.config/ghostty/themes/tron
   ```

2. Add the theme to your Ghostty config (`~/.config/ghostty/config`):
   ```
   theme = tron
   ```

3. Restart Ghostty or reload the configuration

### Method 2: Inline Configuration

Alternatively, you can paste the entire theme directly into your `~/.config/ghostty/config` file.

## Recommended Font

This theme pairs beautifully with monospace fonts that have good ligature support:

- **Fira Code** (used in development)
- JetBrains Mono
- Cascadia Code
- Hack

Add to your config:
```
font-family = "Fira Code"
font-size = 13
```

## Optional Enhancements

For the full TRON grid experience, add these settings to your config:

```
# Slight transparency for that digital grid feel
background-opacity = 0.95
unfocused-split-opacity = 0.7

# Window padding
window-padding-x = 8
window-padding-y = 8
window-padding-balance = true
```

## Color Palette

| Color | Normal | Bright |
|-------|---------|---------|
| Black | `#000000` | `#4D4D4D` |
| Red | `#FF005E` | `#FF2A80` |
| Green | `#00FF9A` | `#2BFFB1` |
| Yellow | `#00FFC8` | `#2BFFE2` |
| Blue | `#00BFFF` | `#33CFFF` |
| Magenta | `#8A2BE2` | `#B266FF` |
| Cyan | `#00FFFF` | `#66FFFF` |
| White | `#E6F8FF` | `#FFFFFF` |

## Screenshots

*Coming soon - submit your screenshots via PR!*

## Contributing

Feel free to open issues or submit pull requests if you have suggestions for improvements!

## License

MIT License - feel free to use and modify as you like.

---

**The Grid awaits...**
