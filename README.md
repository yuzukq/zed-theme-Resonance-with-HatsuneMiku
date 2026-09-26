<h1 align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="./images/logo_dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="./images/logo_light.svg">
    <img alt="Resonance --with_Hatsune_Miku" src="./images/logo_light.svg" width="100%">
  </picture>
</h1>

**Resonance with Hatsune Miku** is a [Zed](https://zed.dev) theme born from a simple wish: as a Miku fan, I want to stay with her even while I'm writing code.
Inspired by Hatsune Miku's color palette — her signature teal paired with vivid pink — it comes in both dark and light variants.

Beyond the colors themselves, every shade is tuned so the code you're reading stays in focus: syntax colors are arranged in three lightness tiers by importance, and the editor pane is set apart from the surrounding panels in even steps.

## Preview

### Dark

![Dark preview](images/preview_dark.png)

### Light

![Light preview](images/preview_light.png)

## Color Palette

| Dark | Light |
| --- | --- |
| <img src="images/palette_dark.svg" alt="Resonance with Hatsune Miku color palette"> | <img src="images/palette_light.svg" alt="Resonance with Hatsune Miku Light color palette"> |

<details>
<summary>All colors as a table</summary>

| Role | Dark | Light |
| --- | --- | --- |
| Editor background | ![#191b1c](https://img.shields.io/badge/-%23191b1c-191b1c?style=flat-square) | ![#fafafa](https://img.shields.io/badge/-%23fafafa-fafafa?style=flat-square) |
| Side panel background | ![#252829](https://img.shields.io/badge/-%23252829-252829?style=flat-square) | ![#e4e9e9](https://img.shields.io/badge/-%23e4e9e9-e4e9e9?style=flat-square) |
| Title bar / Status bar | ![#2a2d2e](https://img.shields.io/badge/-%232a2d2e-2a2d2e?style=flat-square) | ![#dde3e3](https://img.shields.io/badge/-%23dde3e3-dde3e3?style=flat-square) |
| Cursor | ![#39c5bb](https://img.shields.io/badge/-%2339c5bb-39c5bb?style=flat-square) | ![#22a79d](https://img.shields.io/badge/-%2322a79d-22a79d?style=flat-square) |
| Foreground (text) | ![#add6d7](https://img.shields.io/badge/-%23add6d7-add6d7?style=flat-square) | ![#2b4a4c](https://img.shields.io/badge/-%232b4a4c-2b4a4c?style=flat-square) |
| Comments / Muted | ![#68737c](https://img.shields.io/badge/-%2368737c-68737c?style=flat-square) | ![#7d8a93](https://img.shields.io/badge/-%237d8a93-7d8a93?style=flat-square) |
| Accent | ![#458588](https://img.shields.io/badge/-%23458588-458588?style=flat-square) | ![#2f8f8a](https://img.shields.io/badge/-%232f8f8a-2f8f8a?style=flat-square) |
| Keywords / Operators | ![#f92672](https://img.shields.io/badge/-%23f92672-f92672?style=flat-square) | ![#c60355](https://img.shields.io/badge/-%23c60355-c60355?style=flat-square) |
| Strings | ![#81e688](https://img.shields.io/badge/-%2381e688-81e688?style=flat-square) | ![#00791c](https://img.shields.io/badge/-%2300791c-00791c?style=flat-square) |
| Variables | ![#d2fefb](https://img.shields.io/badge/-%23d2fefb-d2fefb?style=flat-square) | ![#1e2f32](https://img.shields.io/badge/-%231e2f32-1e2f32?style=flat-square) |
| Properties | ![#6ddae7](https://img.shields.io/badge/-%236ddae7-6ddae7?style=flat-square) | ![#00679b](https://img.shields.io/badge/-%2300679b-00679b?style=flat-square) |
| Constants | ![#4aa9e0](https://img.shields.io/badge/-%234aa9e0-4aa9e0?style=flat-square) | ![#6f42b2](https://img.shields.io/badge/-%236f42b2-6f42b2?style=flat-square) |
| Types | ![#98e8c9](https://img.shields.io/badge/-%2398e8c9-98e8c9?style=flat-square) | ![#6f42b2](https://img.shields.io/badge/-%236f42b2-6f42b2?style=flat-square) |
| Numbers / Booleans | ![#dba5c8](https://img.shields.io/badge/-%23dba5c8-dba5c8?style=flat-square) | ![#943c80](https://img.shields.io/badge/-%23943c80-943c80?style=flat-square) |
| Functions | ![#00c2b4](https://img.shields.io/badge/-%2300c2b4-00c2b4?style=flat-square) | ![#01736a](https://img.shields.io/badge/-%2301736a-01736a?style=flat-square) |
| **Git Status** | | |
| New file | ![#b8ff89](https://img.shields.io/badge/-%23b8ff89-b8ff89?style=flat-square) | ![#3f9a2e](https://img.shields.io/badge/-%233f9a2e-3f9a2e?style=flat-square) |
| Modified file | ![#74cde6](https://img.shields.io/badge/-%2374cde6-74cde6?style=flat-square) | ![#1a86b0](https://img.shields.io/badge/-%231a86b0-1a86b0?style=flat-square) |
| Deleted file | ![#ffa875](https://img.shields.io/badge/-%23ffa875-ffa875?style=flat-square) | ![#d0602a](https://img.shields.io/badge/-%23d0602a-d0602a?style=flat-square) |
| Error | ![#ff3f3f](https://img.shields.io/badge/-%23ff3f3f-ff3f3f?style=flat-square) | ![#d92b2b](https://img.shields.io/badge/-%23d92b2b-d92b2b?style=flat-square) |

</details>

## Design

The palette was first picked by feel from Miku's colors, then refined with a few principles from visual perception.
All adjustments change only lightness and chroma, never hue, so the Miku palette stays intact.

- **Perceptual lightness (OKLCH)**: Colors are tuned in [OKLCH](https://oklch.com), a perceptually uniform color space, so that "same lightness" actually looks equally bright to the eye.
- **Three tiers by importance**:
  1. **Variables** — the identifiers you read most — get the highest contrast.
  2. **Syntax accents** (keywords, functions, properties, constants, types, strings, numbers) share one lightness band and are told apart by hue.
  3. **Punctuation and comments** step back so they don't compete with names.
- **Helmholtz–Kohlrausch effect**: Highly saturated colors look brighter than their measured lightness. The vivid pink keywords are therefore set lower in lightness so they sit in balance with the other accents instead of glaring.
- **Focus on the editor**: The editor pane is the calmest surface. Tab bar, side panels and title/status bar step away from it in equal lightness steps — darker in the light theme, lighter in the dark theme — so the code area naturally draws the eye.
- **Contrast**: Every token color in the palette meets WCAG AA (4.5:1) against the editor background. Comments are intentionally quieter (about 3.5:1).

## Installation

### From Zed

Open the extensions page (`cmd-shift-x`), search for **"Resonance with Hatsune Miku"** and install it.
You can also open [the extension page on zed.dev](https://zed.dev/extensions/resonance-with-hatsune-miku-theme) and install it from there, which launches Zed.

Then pick the theme with `cmd-k cmd-t`.

> [!NOTE]
> Version 1.0.0 (light variant and refreshed dark palette) is waiting for the extension store update.
> Until it is published, the store serves the previous version, which includes the dark theme only.

### Follow the System Appearance

Both **Resonance with Hatsune Miku** (dark) and **Resonance with Hatsune Miku Light** are included in the extension.
To switch automatically with your system appearance, set both themes in your Zed settings:

```json
{
  "theme": {
    "mode": "system",
    "light": "Resonance with Hatsune Miku Light",
    "dark": "Resonance with Hatsune Miku"
  }
}
```

## Customization

Clone this repository and try your changes in one of two ways:

- **Dev extension**: Click **Install Dev Extension** on Zed's extensions page (or run `zed: install dev extension` from the command palette) and select the cloned directory.
- **Symlink**: Link the theme file into Zed's themes directory. Zed reloads it whenever you save.

  ```sh
  mkdir -p ~/.config/zed/themes
  ln -sf "$PWD/themes/resonance-with-hatsune-miku.json" \
         ~/.config/zed/themes/resonance-with-hatsune-miku.json
  ```

See [THEME_REFERENCE.md](./THEME_REFERENCE.md) for a mapping of color keys to Zed UI elements.

## License

This theme is distributed under the [MIT License](./LICENSE).

This work depicts the character "初音ミク" (Hatsune Miku) of Crypton Future Media, Inc. based on the [Piapro Character License](https://piapro.jp/license/pcl/summary).
This is an unofficial fan work and is not affiliated with or endorsed by Crypton Future Media, Inc.
