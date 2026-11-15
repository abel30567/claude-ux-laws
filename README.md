# Claude UX Laws

The full Markdown instructions behind
[@adam_ha_yes's reel](https://www.instagram.com/reel/DcwkX6OyduT/)
("20 UX Laws to tell Claude for better Design") — as a repo you can
actually hand to Claude, instead of commenting "UX" on a reel and
waiting for a DM.

Give Claude [`ux-laws.md`](ux-laws.md) (or install [`SKILL.md`](SKILL.md)
as a Claude Code skill) and it designs with 20 proven UX laws applied,
not just vibes.

## The 20 laws

| # | Law | The rule for Claude |
|---|-----|---------------------|
| 1 | Hick's law | Reduce choices per screen |
| 2 | Fitts's law | Make targets large; place key actions nearby |
| 3 | Jakob's law | Follow familiar patterns |
| 4 | Law of proximity | Group related information |
| 5 | Miller's law | Break content into chunks |
| 6 | Doherty threshold | Interactions within 400 ms |
| 7 | Von Restorff effect | Highlight the primary action |
| 8 | Minimize target distance | Place key actions nearby |
| 9 | Serial position effect | Put essentials first |
| 10 | Peak-end rule | End flows memorably |
| 11 | Zeigarnik effect | Show visible progress; make completion feel closer |
| 12 | Law of Prägnanz | Simplify complex interfaces |
| 13 | Law of similarity | Maintain pattern consistency |
| 14 | Law of uniform connectedness | Connect related elements visually |
| 15 | Tesler's law | Use sensible defaults |
| 16 | Postel's law | Prevent errors proactively; make errors recoverable |
| 17 | Postel's law (again) | *See note below* |
| 18 | Parkinson's law | Reduce task completion time |
| 19 | Occam's Razor | Reveal complexity gradually |
| 20 | Pareto principle | Put essentials first — the 20% that does 80% of the work |

**Note on #17:** the reel lists Postel's law twice (#16 and #17).
This repo keeps the 19 unique laws and flags the duplicate rather
than pretending there are 20 distinct ones. #8 is also phrased in the
reel as an instruction ("Minimize target distance") rather than a law
name — it is Fitts's law applied, and is kept as its own rule.

## How to use it

**Option 1 — paste it into Claude.** Copy [`ux-laws.md`](ux-laws.md)
into your prompt or project instructions:
"Design this UI following these UX laws: [paste]".

**Option 2 — Claude Code skill.** Copy `SKILL.md` to
`~/.claude/skills/ux-laws/SKILL.md`. Claude Code picks it up
automatically when you ask it to design or review a UI.

**Option 3 — project instructions.** Drop `ux-laws.md` into your
repo as `CLAUDE.md` (or reference it from there) so every UI Claude
builds in the project follows the laws.

## What Claude does with it

Before finishing any UI, Claude runs the checklist at the end of
`SKILL.md`: choices per screen, target sizes, familiar patterns,
grouping, chunking, feedback timing, primary action, error handling,
progress, and the 80/20 cut. If a design breaks a law, it says which
one and fixes it.

## Worked example

[`examples/landing-page-checklist.md`](examples/landing-page-checklist.md)
applies the laws to a landing page, law by law.

## License

MIT — see [LICENSE](LICENSE). The laws themselves are public
psychology/design knowledge; the write-ups here are original.
