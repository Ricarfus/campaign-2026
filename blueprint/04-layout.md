# Layout

## Principles
1. **Space first.** At least 40% of any piece is empty.
2. **One focal point.** Either the names, a photo, or one line. Not all three competing.
3. **Align to edges.** Text sits hard against a margin, usually bottom-left or top-left. Avoid a centered stack of everything.
4. **Square corners.** Radius 0 on photos and blocks. Only buttons on the website get a small radius.
5. **Hairlines, not boxes.** Separate with a thin `rule` line or space, not borders around things.

## Spacing scale (8px base)

| Token | Value | Use |
| --- | --- | --- |
| `space-1` | 4px | Label to its text. |
| `space-2` | 8px | Tight groups. |
| `space-3` | 16px | Between lines of a group. |
| `space-4` | 24px | Between groups. |
| `space-5` | 40px | Section gaps, social margins. |
| `space-6` | 64px | Big gaps, poster inner margin (scaled). |
| `space-7` | 104px | Hero spacing on the website. |

## Margins
- Social (1080px wide): 72px outer margin.
- Posters / flyers: margin = 6% of the short side (11×17 → about 0.66in).
- Website: 24px on phones, max content width 1120px.

## Radii

| Token | Value | Use |
| --- | --- | --- |
| `radius-0` | 0 | Everything by default. |
| `radius-sm` | 2px | Website inputs. |
| `radius-md` | 4px | Website buttons. |

## Photos
- Candid or plainly posed, not grinning headshots. Looking slightly off-camera is good.
- Black and white or muted natural color. Same treatment across a series.
- Full-bleed or cropped hard to a grid edge. Never in circles, never with borders or stickers.

## Recurring elements (the "signature")
- The `POTIÉ / BIGGAR` label in a corner, the same corner on every piece of a series.
- A thin `rule` line across the piece.
- An occasional solid `forest` block holding a single line.
These three repeated everywhere are what make the campaign recognizable.
