# Eclipse Dataspace Hub — brand kit

The Orbit mark: a hub (violet core) with open-source projects (satellites) on a shared ring.

## Contents

| Folder | What's inside |
|---|---|
| `svg/` | Master vector files. Text is outlined, so no fonts are needed. |
| `png/` | Raster exports by asset, at several sizes, with transparent backgrounds (except the app icon and avatar). |
| `favicon/` | `favicon.svg`, `favicon.ico` (16/32/48), PNG favicons, `apple-touch-icon.png`, 192/512 icons, `site.webmanifest`, `head-snippet.html`. |
| `social/` | Open Graph / Twitter card, 1200×630 (SVG, PNG, @2x PNG). |

### Which file to use

- **On light backgrounds:** `lockup-horizontal`, `lockup-stacked`, `wordmark`, `mark`
- **On dark backgrounds:** the `-reversed` versions
- **One-color printing / embossing:** `mark-mono-ink`, `mark-mono-white`
- **GitHub org / social avatar:** `png/avatar/avatar-500.png` (cropped to a circle automatically)
- **App or store icon:** `app-icon` (rounded corners) or `app-icon-square` (full bleed, for platforms that apply their own mask)
- **Below 32 px:** use the favicon cut (`favicon/` or `svg/favicon-on-*.svg`). It has heavier strokes and larger satellites so it stays readable.

## Color

| Name | Hex | RGB | Use |
|---|---|---|---|
| Ink | `#14121C` | 20 18 28 | Primary text, dark backgrounds |
| Paper | `#F6F5F2` | 246 245 242 | Light backgrounds, reversed marks |
| Violet | `#7B5CFF` | 123 92 255 | Brand accent: the core of the mark |
| Slate | `#5B5868` | 91 88 104 | Secondary text on light ("Eclipse" line) |
| Mist | `#B4B0C2` | 180 176 194 | Secondary text on dark |
| Line | `#E2E0DA` | 226 224 218 | Dividers and hairlines |

Support accents, used sparingly: Ember `#FF6B3D` and Jade `#18B37E`.

## Type

- **Geist**: wordmark, headlines and body. Display sizes use −0.04em tracking.
- **Geist Mono**: labels, code and endpoints.

Both are free under the SIL Open Font License, from [Google Fonts](https://fonts.google.com/specimen/Geist) or [vercel/geist-font](https://github.com/vercel/geist-font).

## Wordmark

"Eclipse" sits above "Dataspace Hub" at 42% of its size, in Geist Medium, Slate on light or Mist on dark. "Dataspace" is set in Geist Regular and "Hub" in Geist SemiBold. Always write the name in mixed case: **Eclipse Dataspace Hub**.

## Clear space and minimum size

- Keep clear space of one satellite diameter around the mark on every side.
- Minimum size is 16 px for the favicon cut, 32 px for the standard mark and 120 px wide for the horizontal lockup.
- Don't recolor the satellites, change the ring, rotate the mark or set the wordmark in another font.
