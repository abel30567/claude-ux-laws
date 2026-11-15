# UX Laws — instructions for Claude

Copy this file into your prompt, project instructions, or `CLAUDE.md`
and Claude will design with 20 proven UX laws applied. Each law has
what it says, the rule to follow, and what to check.

Source: "20 UX Laws to tell Claude for better Design" by @adam_ha_yes.
Two corrections to the reel's list: Postel's law appears twice (#16
and #17), so there are 19 unique laws; #8 is phrased in the reel as an
instruction rather than a law name and is kept as its own rule.

---

## 1. Hick's law
**What it says:** decision time grows with the number of choices.
**Rule:** reduce choices per screen. One primary action, a few secondary.
**Check:** can the user tell what to do next within 2 seconds?

## 2. Fitts's law
**What it says:** time to hit a target depends on its size and distance.
**Rule:** make targets large (min 44×44 px touch) and put key actions
where the pointer already is.
**Check:** is the primary button big and close to the content it acts on?

## 3. Jakob's law
**What it says:** users prefer interfaces that work like ones they know.
**Rule:** follow familiar patterns. Nav top/left, logo links home,
search top-right, submit bottom-right of a form.
**Check:** would a first-time user already know where things are?

## 4. Law of proximity
**What it says:** objects near each other are perceived as related.
**Rule:** group related information. Label next to its field, price next
to its product, error next to the input that caused it.
**Check:** is every label, price, and error sitting next to what it
describes?

## 5. Miller's law
**What it says:** working memory holds about 7±2 chunks.
**Rule:** break content into chunks. Long forms become steps, long lists
become sections, dashboards become cards.
**Check:** is there any undifferentiated wall of 10+ items?

## 6. Doherty threshold
**What it says:** responses within 400 ms keep users in flow.
**Rule:** interactions within 400 ms. Every click gets instant feedback
— state change, skeleton, spinner — even if the work takes longer.
**Check:** does any click do nothing visible?

## 7. Von Restorff effect
**What it says:** the distinctive item is remembered.
**Rule:** highlight the primary action. One element per screen gets the
strongest treatment.
**Check:** is there exactly one thing shouting on this screen?

## 8. Minimize target distance
**What it says:** (Fitts's law applied) shorter travel = faster, more
accurate clicks.
**Rule:** place key actions nearby. The action for a piece of content
sits next to that content, not in a distant toolbar.
**Check:** does the user have to travel across the screen to act?

## 9. Serial position effect
**What it says:** first and last items in a sequence are remembered best.
**Rule:** put essentials first — most important nav item, list item,
and fact go first.
**Check:** is the most important thing first?

## 10. Peak-end rule
**What it says:** people judge an experience by its peak and its ending.
**Rule:** end flows memorably. Confirmation and success states should
feel good, not blank.
**Check:** does the last screen of the flow feel like a finish?

## 11. Zeigarnik effect
**What it says:** unfinished tasks stick in memory; people want closure.
**Rule:** show visible progress and make completion feel closer.
Multi-step flows get a progress indicator; long tasks get milestones.
**Check:** does the user always know how much is left?

## 12. Law of Prägnanz
**What it says:** people perceive simple, ordered forms over complex ones.
**Rule:** simplify complex interfaces. One idea per screen, aligned grids,
consistent spacing.
**Check:** does the screen need a legend to be understood? If yes, it is
too complex.

## 13. Law of similarity
**What it says:** elements that look alike are perceived as related.
**Rule:** maintain pattern consistency. Same kind of thing, same look.
A visual difference must mean a functional difference.
**Check:** do two identical-looking elements do different things? Fix it.

## 14. Law of uniform connectedness
**What it says:** visually connected elements are perceived as a group.
**Rule:** connect related elements visually — borders, backgrounds, lines
— instead of hoping proximity alone does it.
**Check:** is each group visibly a group?

## 15. Tesler's law
**What it says:** complexity can't be removed, only moved — to the user
or to the system.
**Rule:** use sensible defaults. Prefill what you know, pick the most
likely option, ask only what only the user can answer.
**Check:** is the user being asked anything the system could have filled in?

## 16. Postel's law
**What it says:** be liberal in what you accept, conservative in what
you send.
**Rule:** prevent errors proactively and make errors recoverable.
Validate as the user types, accept common formats, and when something
fails, say what happened and offer one click to fix it — never a dead end.
**Check:** can every error be fixed in one click from the error itself?

## 17. Postel's law — duplicate
The source reel lists Postel's law twice. There is no twentieth distinct
law here; do not invent one.

## 18. Parkinson's law
**What it says:** work expands to fill the time available.
**Rule:** reduce task completion time. Fewer steps, fewer fields, fewer
decisions. If a flow takes 5 steps and can take 3, it takes 3.
**Check:** can any step be removed without losing anything?

## 19. Occam's Razor
**What it says:** the simplest solution is usually the best.
**Rule:** reveal complexity gradually. Common path first; advanced options
behind a clear "Advanced" disclosure.
**Check:** is the advanced stuff hidden until asked for?

## 20. Pareto principle
**What it says:** roughly 80% of effects come from 20% of causes.
**Rule:** put essentials first. The 20% of features that do 80% of the
work get the most space; the rest gets less space, a submenu, or the cut.
**Check:** is the most-used 20% the most prominent thing on screen?

---

## Pre-delivery checklist (run before finishing any UI)

- [ ] One primary action per screen, highlighted
- [ ] Touch targets ≥ 44×44 px; key actions near their content
- [ ] Follows familiar patterns
- [ ] Related items grouped by proximity and visual connection
- [ ] Content chunked; no undifferentiated walls
- [ ] Every interaction acknowledges within 400 ms
- [ ] Essentials first; flow ends well
- [ ] Progress visible on multi-step flows
- [ ] Simple at first glance; advanced options disclosed
- [ ] Repeated elements look identical
- [ ] Sensible defaults everywhere
- [ ] Errors prevented where possible, recoverable in one click when not
- [ ] The flow is as short as it can be
- [ ] The 20% that matters is the most prominent thing on screen
