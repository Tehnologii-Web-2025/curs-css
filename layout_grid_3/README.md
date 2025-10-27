# Grid Exercise 3 — Named Lines & Areas

Refine the dashboard layout with named grid lines and template areas for clearer semantics.

## Requirements

- Define the columns with named lines, e.g. `[main-start] 1fr [content-start] repeat(4, 1fr) [content-end] 1fr [main-end]`, and keep the three-row structure (`150px 1fr 100px`).
- Map the header, menu, content, and footer to semantic `grid-template-areas` (H, M, C, F) and assign each child via `grid-area`.
- Use a visible `gap` so the underlying grid tracks and the effect of the named lines are easy to explain.
