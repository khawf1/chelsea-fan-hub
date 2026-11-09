---
name: color-palettes
description: The user's saved color palettes ("Deep Teal & Rust", "Midnight Navy & Amber"). Use when choosing colors, theming a UI, building design tokens, or when the user mentions "my palettes", "the teal palette" or "the navy palette".
---

# Saved color palettes

Two dark-to-light palettes, each ordered darkest → lightest, with one warm accent.
Roles: 1 = page background, 2 = surface/card, 3 = border/muted, 4 = primary/link,
5 = text on dark / light background, 6 = accent (buttons, highlights, CTAs).

## Palette A — Deep Teal & Rust

| Role | Hex |
|---|---|
| Background | `#0A0F14` |
| Surface | `#0F3D3E` |
| Muted / border | `#2E6F73` |
| Primary | `#7FB3B8` |
| Text / light | `#EADCC8` |
| Accent | `#C6601F` |

```css
:root {
  --bg: #0A0F14;
  --surface: #0F3D3E;
  --muted: #2E6F73;
  --primary: #7FB3B8;
  --text: #EADCC8;
  --accent: #C6601F;
}
```

## Palette B — Midnight Navy & Amber

| Role | Hex |
|---|---|
| Background | `#0B132B` |
| Surface | `#1C2541` |
| Muted / border | `#3A506B` |
| Primary | `#5BC0DE` |
| Text / light | `#F4D6B0` |
| Accent | `#D97706` |

```css
:root {
  --bg: #0B132B;
  --surface: #1C2541;
  --muted: #3A506B;
  --primary: #5BC0DE;
  --text: #F4D6B0;
  --accent: #D97706;
}
```

## Usage notes

- Both are dark-first. For a light theme, swap: background = Text/light, text = Background, keep Accent.
- Check contrast: the Accent on Background passes for large text and buttons; for small body text use Text/light on Background.
- Use the accent sparingly (about 10% of the screen): CTAs, active states, key numbers.
