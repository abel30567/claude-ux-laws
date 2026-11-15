# Worked example: landing page, law by law

A signup landing page for a budgeting app, before and after the laws.

## Before (what Claude usually ships)

- Hero with 6 nav links, 2 CTAs, a carousel, and a 12-field signup form
- "Sign up" button is the same size and color as "Learn more"
- Pricing shown as a wall of 9 undifferentiated feature bullets
- Form errors appear at the top of the page, away from the fields
- No feedback when the submit button is clicked until the server replies

## After (laws applied)

| Law | Change |
|-----|--------|
| Hick's | One primary CTA ("Start free"), one secondary ("See how it works"). Nav cut to 4 links. |
| Fitts's | Primary CTA is a large button directly under the hero copy, where the eye lands. |
| Jakob's | Nav top, logo links home, pricing link where users expect it. |
| Proximity | Each form error sits under its own field. Price sits next to its plan name. |
| Miller's | Signup split into 2 steps: account, then preferences. Pricing features chunked into 3 groups. |
| Doherty | Submit button shows "Creating your account…" instantly. |
| Von Restorff | Only the primary CTA is solid color; everything else is ghost/outline. |
| Minimize target distance | "Start free" sits next to the hero headline, not in a distant header. |
| Serial position | First pricing tier is the popular plan; first feature listed is the one users ask about most. |
| Peak-end | Success screen says "You're in — your first budget is ready" with one clear next step. |
| Zeigarnik | 2-step signup shows "Step 1 of 2" with a progress bar. |
| Prägnanz | One idea per section; consistent 8px spacing grid. |
| Similarity | All three pricing cards identical in structure; only the popular one gets a badge. |
| Uniform connectedness | Each pricing card is a bordered group; features inside belong to that card. |
| Tesler's | Currency defaults to the visitor's locale; trial length pre-selected at 14 days. |
| Postel's | Email field accepts "name@gmail" and suggests the fix; a failed submit keeps the form filled and says exactly what to correct. |
| Parkinson's | Signup is 2 steps instead of 4; optional fields moved to after signup. |
| Occam's Razor | Advanced settings (categories, import) live behind "Advanced" on the success screen, not the landing page. |
| Pareto | The hero sells the one feature 80% of users come for (automatic budgets); the rest lives below the fold. |

## The prompt that produced the "after"

> Design a signup landing page for a budgeting app. Follow the UX laws
> in ux-laws.md and run the pre-delivery checklist before finishing.
