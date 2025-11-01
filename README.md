# Tron Themes for Ghostty

A collection of neon-inspired terminal themes for [Ghostty](https://ghostty.org/) based on the iconic TRON aesthetic. Choose your side of the Grid!

![Theme Preview](preview.png)

## Theme Variants

### 🔵 Tron (Classic Blue)
The original Grid aesthetic - vibrant cyan neon representing the Users and their allies.
- Pure black background with bright cyan foreground (`#E6F8FF`)
- Neon cyan cursor (`#00EFFF`)
- Optimized for readability during extended coding sessions

### 🟠 Tron Orange (Clu's Forces)
Inspired by Clu's army and the antagonists of Tron Legacy.
- Warm orange/amber neon (`#FFB366`) on pure black
- Fierce orange cursor (`#FF6600`)
- Perfect for when you're feeling rebellious

### 🔴 Tron Red (Rinzler)
Deep red neon inspired by corrupted programs and Rinzler.
- Blood-red accents (`#FF6B6B`) with intense red cursor (`#FF0000`)
- For those who've crossed to the dark side

## Features

- **Pure black background** (`#000000`) for maximum contrast
- **Full ANSI color palette** with bright, vivid neon colors
- **Three distinct color schemes** to match your mood
- Optimized for both readability and style

## Installation

### Method 1: Direct Theme File

1. Copy your chosen theme(s) to your Ghostty themes directory:
   ```bash
   mkdir -p ~/.config/ghostty/themes

   # Choose one or install all three:
   cp tron.conf ~/.config/ghostty/themes/tron
   cp tron-orange.conf ~/.config/ghostty/themes/tron-orange
   cp tron-red.conf ~/.config/ghostty/themes/tron-red
   ```

2. Add the theme to your Ghostty config (`~/.config/ghostty/config`):
   ```
   # Classic blue
   theme = tron

   # Or orange variant
   # theme = tron-orange

   # Or red variant
   # theme = tron-red
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

## Color Palettes

### Tron (Classic Blue)
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

### Tron Orange
| Color | Normal | Bright |
|-------|---------|---------|
| Black | `#000000` | `#4D1F00` |
| Red | `#FF3300` | `#FF5522` |
| Green | `#FF9933` | `#FFAA44` |
| Yellow | `#FFCC00` | `#FFDD33` |
| Blue | `#FF6600` | `#FF8833` |
| Magenta | `#CC3300` | `#EE4422` |
| Cyan | `#FF9966` | `#FFAA77` |
| White | `#FFB366` | `#FFDDBB` |

### Tron Red
| Color | Normal | Bright |
|-------|---------|---------|
| Black | `#000000` | `#4D0000` |
| Red | `#FF0000` | `#FF2222` |
| Green | `#FF3333` | `#FF5555` |
| Yellow | `#FF6666` | `#FF8888` |
| Blue | `#CC0000` | `#EE1111` |
| Magenta | `#990000` | `#BB0000` |
| Cyan | `#FF9999` | `#FFAAAA` |
| White | `#FFCCCC` | `#FFDDDD` |

## Screenshots

*Coming soon - submit your screenshots via PR!*

## Contributing

Feel free to open issues or submit pull requests if you have suggestions for improvements!

## License

MIT License - feel free to use and modify as you like.

---

**The Grid awaits...**
