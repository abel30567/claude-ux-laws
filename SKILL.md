---
name: ux-laws
description: Design or review any UI using 20 proven UX laws (Hick's, Fitts's, Jakob's, Miller's, Doherty, Von Restorff, Peak-end, Zeigarnik, Pareto, and more). Use when building, redesigning, or critiquing interfaces, pages, flows, forms, or components — apply the laws, then run the checklist before finishing.
---

# UX Laws — design skill

You design interfaces using 20 UX laws. Every UI you build or review
must follow them. When a law conflicts with a request, say so and
follow the law unless the user explicitly overrides it.

## The laws

### 1. Hick's law
Time to decide grows with the number of choices.
**Rule:** reduce choices per screen. One primary action, at most a few
secondary ones. If a screen has more than 5 competing choices, group or
cut them.

### 2. Fitts's law
Time to hit a target depends on its size and distance.
**Rule:** make targets large (min 44×44 px touch targets) and put key
actions where the pointer already is — near the content they act on.

### 3. Jakob's law
Users prefer interfaces that work like the ones they already know.
**Rule:** follow familiar patterns. Nav on top or left, logo links home,
search top-right, primary button bottom-right of a form. Don't invent a
new pattern to be clever.

### 4. Law of proximity
Objects near each other are perceived as related.
**Rule:** group related information. Put a label next to its field, a
price next to its product, an error next to the input that caused it.
Whitespace is the grouping tool — use it deliberately.

### 5. Miller's law
Working memory holds about 7±2 chunks.
**Rule:** break content into chunks. Long forms become steps, long lists
become sections, dashboards become cards. Never show a wall of 20
undifferentiated items.

### 6. Doherty threshold
If a system responds within 400 ms, users stay in flow.
**Rule:** interactions within 400 ms. Every click gets instant feedback
— a state change, a skeleton, a spinner — even if the real work takes
longer. Never leave a dead click.

### 7. Von Restorff effect
The distinctive item is the one remembered.
**Rule:** highlight the primary action. One element per screen gets the
strongest treatment (color, size, contrast). If everything is bold,
nothing is.

### 8. Minimize target distance
Shorter travel to a target means faster, more accurate clicks.
**Rule:** place key actions nearby. The action for a piece of content
sits next to that content, not in a distant toolbar.

### 9. Serial position effect
People remember the first and last items in a sequence best.
**Rule:** put essentials first. The most important nav item, the most
important list item, the most important fact — first. (The last item
matters too: see Peak-end.)

### 10. Peak-end rule
People judge an experience by its most intense moment and its ending.
**Rule:** end flows memorably. The confirmation screen, the success
state, the last step — make it feel good, not blank. A great ending
lifts the whole flow.

### 11. Zeigarnik effect
Unfinished tasks stick in memory; people want closure.
**Rule:** show visible progress and make completion feel closer.
Multi-step flows get a progress indicator; long tasks get milestones.
Never leave a user wondering how much is left.

### 12. Law of Prägnanz
People perceive simple, ordered forms over complex ones.
**Rule:** simplify complex interfaces. One idea per screen, aligned
grids, consistent spacing. If a screen needs a legend to be understood,
it is too complex.

### 13. Law of similarity
Elements that look alike are perceived as related.
**Rule:** maintain pattern consistency. Same kind of thing, same look:
all primary buttons identical, all cards identical, all errors identical.
A visual difference must mean a functional difference.

### 14. Law of uniform connectedness
Elements connected visually are perceived as a group.
**Rule:** connect related elements visually. Borders, backgrounds, and
lines group things; use them instead of hoping proximity alone does it.

### 15. Tesler's law (conservation of complexity)
Complexity cannot be removed, only moved — to the user or to the system.
**Rule:** use sensible defaults. Move complexity into the system: prefill
what you know, pick the most likely option, ask only what only the user
can answer.

### 16. Postel's law (robustness principle)
Be liberal in what you accept, conservative in what you send.
**Rule:** prevent errors proactively and make errors recoverable.
Validate as the user types, accept common formats (phone numbers with
or without dashes), and when something fails, say what happened and
offer one click to fix it — never a dead end.

### 17. (Duplicate — Postel's law, listed twice in the source reel)
The source reel lists Postel's law at both #16 and #17. There are 19
unique laws here, not 20. Do not invent a twentieth.

### 18. Parkinson's law
Work expands to fill the time available.
**Rule:** reduce task completion time. Fewer steps, fewer fields, fewer
decisions. If a flow takes 5 steps and can take 3, it takes 3.

### 19. Occam's Razor
The simplest solution is usually the best.
**Rule:** reveal complexity gradually. Show the common path first;
advanced options live behind a clear "Advanced" disclosure. Simple by
default, powerful on demand.

### 20. Pareto principle (80/20)
Roughly 80% of effects come from 20% of causes.
**Rule:** put essentials first. Find the 20% of features that do 80% of
the work and make them prominent; the rest gets less space, a submenu,
or the cut.

## Pre-delivery checklist

Before you finish any UI, check each item. If one fails, fix it or say
why it can't be fixed.

- [ ] One primary action per screen, highlighted (Hick's, Von Restorff)
- [ ] Touch targets ≥ 44×44 px; key actions near their content (Fitts's, #8)
- [ ] Follows familiar patterns — nothing re-invented without a reason (Jakob's)
- [ ] Related items grouped by proximity and visual connection (Proximity, Uniform connectedness)
- [ ] Content chunked; no wall of undifferentiated items (Miller's)
- [ ] Every interaction acknowledges within 400 ms (Doherty)
- [ ] Essentials first, flow ends well (Serial position, Peak-end)
- [ ] Progress is visible on multi-step flows (Zeigarnik)
- [ ] Screen is simple at first glance; advanced options disclosed (Prägnanz, Occam's Razor)
- [ ] Repeated elements look identical (Similarity)
- [ ] Sensible defaults everywhere; only ask what only the user knows (Tesler's)
- [ ] Errors prevented where possible, recoverable in one click when not (Postel's)
- [ ] The flow is as short as it can be (Parkinson's)
- [ ] The 20% that matters is the most prominent thing on screen (Pareto)
