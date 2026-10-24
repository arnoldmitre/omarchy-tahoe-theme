# Tahoe (macOS Liquid Glass)

An alpine, crystal-clear theme for [Omalauncher](https://github.com/omacom/omarchy) inspired by the macOS Tahoe Liquid Glass aesthetic and the crystalline azure waters of Lake Tahoe.

Features frosted liquid glass translucency, crisp ice-edge highlights, Sierra granite slate tones, and signature macOS vibrant system accents.

## Palette

| Element | Hex | Preview / Description |
|---|---|---|
| **Accent (Electric Blue)** | `#0a84ff` | macOS Tahoe primary highlight |
| **Active Glow** | `#38bdf8` | Lake Tahoe shallow crystal cyan |
| **Background (Midnight Depths)** | `#0b1320` | Translucent deep lake obsidian |
| **Card Surface (Glass Tint)** | `#142033` | Elevated liquid glass layer |
| **Foreground (Alpine Snow)** | `#f0f6fc` | Crisp, high-contrast typography |
| **Muted / Granite** | `#526b8e` | Sierra Nevada rock slate |
| **Selection** | `#1e3a5f` | Glacial blue selection wash |

## Highlights

- **Frosted Glass Blur**: Seamless integration with Omalauncher's `frost = true` blur engine.
- **Dynamic Liquid Glow**: 45-degree cyan/blue active borders mimicking glass refraction.
- **macOS System Accents**: Carefully matched red (`#ff453a`), emerald green (`#30d158`), golden sun (`#ffd60a`), and electric purple (`#bf5af2`).
- **Lake Tahoe Wallpapers**: Includes both panoramic 16:9 and vertical mobile wallpapers capturing the alpine liquid glass atmosphere.

## Style Configuration (`~/.config/omalauncher/style/style.toml`)

```toml
version = 1
theme = "tahoe"
font = "DejaVu Sans Mono"

[home]
app-tiles = true

[widgets]
opacity = 0.68
frost = true
border-width = 1
border = "theme"
border-focused = "theme"

[corners]
scale = 0.85

[status-bar]
framed = true
opacity = 0.68
border-width = 1

[navigation-bar]
framed = true
opacity = 0.68
border-width = 1
```
