# Grid Exercise 2 — 12-Column Layout

Evolve the previous layout into a responsive 12-column grid that mimics a common page shell.

## Requirements

- Use `grid-template-columns: repeat(12, 1fr)` and rows `100px 1fr 100px` across the full viewport.
- Place the areas: header `1 / -1`, menu `1 / span 3`, content `4 / -1`, footer `1 / -1`.
- Fill the header with three inline items (Home, Search, Logout), align them with flexbox, and push “Logout” to the far edge via `margin-left: auto`.
- Keep gaps consistent so the column structure remains visible when resizing the viewport.
