# Color

Near-monochrome with one accent. The look comes from space and type, not color. Every piece must still work if photocopied in black and white.

## Light theme — "Paper" (default for print)

| Token | Hex | Use |
| --- | --- | --- |
| `paper` | `#F1EFEA` | Background. Warm off-white, not pure white. |
| `paper-2` | `#E4E1DA` | Second surface: panels, cards, bands. |
| `ink` | `#121212` | Headlines, body text, names. |
| `ink-muted` | `#55524C` | Small labels, captions, dates. |
| `rule` | `#C9C5BC` | Hairlines and dividers only. Never text. |
| `stone` | `#A39E93` | Decorative blocks and texture only. Never text (too light). |
| `forest` | `#23372B` | The one accent. Big solid blocks or a single highlighted word. |
| `on-forest` | `#F1EFEA` | Text on a `forest` block. |

## Dark theme — "Ink" (social, website dark mode)

| Token | Hex | Use |
| --- | --- | --- |
| `paper` | `#121212` | Background. |
| `paper-2` | `#1E1E1C` | Second surface. |
| `ink` | `#EDEAE4` | Main text. |
| `ink-muted` | `#A8A39A` | Labels, captions. |
| `rule` | `#3A3834` | Hairlines. |
| `stone` | `#6B675F` | Decorative only. |
| `forest` | `#7E9C86` | Accent, lightened to read on dark. |
| `on-forest` | `#121212` | Text on a `forest` block. |

## Rules
- A piece uses **paper + ink**, plus **at most one** of `forest` or `stone`. Never all at once.
- `forest` takes big areas or one word. Never outlines, never gradients, never small decorations.
- No other colors. No school colors, no reds, pinks, yellows, bright blues.
- No gradients, glows or drop shadows.
- Photos can be black and white or natural color, slightly muted. Never oversaturated or filtered.

## Contrast (checked)
Every text pair passes WCAG AA in both themes: ink on paper 16:1 / 15.6:1, ink-muted on paper 6.8:1 / 7.5:1, forest on paper 11:1 / 6.2:1, on-forest on forest 11:1 / 6.2:1.

_v0: provisional. Swap values here AND in `tokens/` once references are sorted._
