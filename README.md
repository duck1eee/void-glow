# Void Glow

A near-black deep-space theme for [Orca](https://github.com/stablyai/orca): a realistic starfield with
drifting cosmic dust as a looping wallpaper, a matching terminal palette, and a pure OLED black variant.

## Themes

| Theme | Description |
| --- | --- |
| `Void Glow` | Near-black (`#050507`) with the wallpaper and violet accents |
| `Void Glow (dark sidebar)` | Same, with a dark neutral sidebar |
| `Void Glow (light sidebar)` | Same, with a light sidebar |
| `Void Glow OLED (pure black)` | True black `#000000`, no wallpaper |

Terminal palettes: `Void Glow` and `Void Glow OLED`.

## Use

Select a theme under **Settings → Appearance → Interface → Dark theme** and the matching palette under
**Terminal Themes**. The wallpaper shows only when **Background Opacity** is below 1 and
**Reduce Visual Effects** is off.

## Develop

```sh
orca plugin validate .
orca plugin dev watch .
```
