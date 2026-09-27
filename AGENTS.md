# Rules for AI agents working in this repo

This file is read by OpenCode, Claude Code and any other agent. `CLAUDE.md` points here.

## Source of truth
- `blueprint/` is the source of truth for every visual and written decision. Read `blueprint/00-brief.md` first, then the file relevant to the task.
- Use values from `blueprint/tokens/tokens.json` (or `tokens.css` for web). Never invent a new color, font, size or spacing value inside a build.
- If a task needs something the blueprint doesn't cover, stop and propose a blueprint change instead of improvising.

## Changing the blueprint
- Only change `blueprint/` when a human asks for it.
- Every blueprint change gets a line in `DECISIONS.md` (date, who, what, why) and a bump of the version at the top of `blueprint/00-brief.md`.
- Keep `tokens.json` and `tokens.css` in sync — change both in the same commit.

## References
- New files land in `references/inbox/`. When sorting, move them to `keep/` or `avoid/` and add a row to `references/REFERENCES.md` naming the ONE specific thing we like or reject in it ("the tight all-caps label above the headline", not "nice vibe").
- References are inspiration. Never copy a logo, photo, character or layout wholesale.

## Builds
- Finished work goes in `builds/<type>/`, named `YYYY-MM-DD_short-name.ext` (e.g. `2026-10-06_poster-launch.pdf`).
- Run `blueprint/06-checklist.md` against every build before calling it done.

## Git
- Small commits with plain messages: `blueprint: tighten headline sizes`, `refs: sort inbox`, `build: launch poster v1`.
- Pull before you start; two people and two agents work here.
- Don't commit large source files over ~20 MB; put a link in a `.md` instead.
