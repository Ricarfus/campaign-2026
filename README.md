# campaign-2026
A campaign nobody has ever made.

Rufus Potié for President. Hudson Biggar for Vice President.

This repo holds everything that makes our campaign look and sound like one thing. **Read `blueprint/` before you make anything.**

## Map

| Folder | What goes here |
| --- | --- |
| `blueprint/` | The rules: brief, voice, color, type, layout, formats, checklist, tokens. The source of truth. |
| `references/inbox/` | Drop anything you like or hate here, unsorted. Screenshots, fonts, photos, links in a `.md`. |
| `references/keep/` | Sorted references we want to borrow from, each logged in `references/REFERENCES.md`. |
| `references/avoid/` | What we are deliberately *not* doing (competitor styles, cheesy templates). |
| `assets/` | Final approved raw materials: logo, fonts, photos, icons, textures. Only approved stuff. |
| `builds/` | Finished pieces: posters, flyers, social, website. Empty until the blueprint is locked. |
| `DECISIONS.md` | Every style decision, who made it, and why. |

## How we work

1. Drop references in `references/inbox/`.
2. Sort them into `keep/` or `avoid/`, one line each in `REFERENCES.md` saying *what exactly* we like.
3. Anything that changes the look gets written into `blueprint/` and logged in `DECISIONS.md`.
4. Only build in `builds/` from the blueprint. If a piece needs something the blueprint doesn't cover, update the blueprint first.

Both of us use AI agents (Claude Code, OpenCode). They follow `AGENTS.md`.

## Status

Blueprint **v0 — provisional**. Colors and fonts are a starting direction based on the brief, waiting on our references. Nothing in `builds/` yet.
