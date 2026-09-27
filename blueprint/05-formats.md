# Formats

Specs for every deliverable. Check current platform sizes before exporting; social specs change.

| Deliverable | Size | Export | Notes |
| --- | --- | --- | --- |
| Instagram post | 1080 × 1350 px (4:5) | PNG | Keep key content inside the center 1080 × 1080 so grid crops don't cut it. |
| Instagram story / TikTok cover | 1080 × 1920 px | PNG | Keep text out of the top 250px and bottom 340px (app UI). |
| Instagram carousel | 1080 × 1350 px per slide | PNG | Same corner label on every slide. |
| Poster | 11 × 17 in (tabloid) | PDF, 300 dpi | Confirm school size limits. Add 0.125in bleed if a print shop prints it. |
| Large poster | 18 × 24 in | PDF, 300 dpi | Print shop only. |
| Flyer | 8.5 × 11 in (letter) | PDF, 300 dpi | Must work on a black-and-white copier. |
| Handout / quarter sheet | 4.25 × 5.5 in | PDF | 4-up on letter. |
| Website | Responsive, 360px to 1440px | HTML/CSS | Use `tokens/tokens.css`. |

## Black-and-white test
Before printing anything on a copier, convert to grayscale and check it still reads. `forest` becomes near-black, so a `forest` block with `on-forest` text still works.

## File naming
`YYYY-MM-DD_format_short-name.ext` → `2026-10-06_poster_launch.pdf`
