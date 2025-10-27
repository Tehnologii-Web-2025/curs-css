# Flex Layout Drill

Goal: turn the five blocks into a flexible row that adapts to the viewport while demonstrating the most common flex container and flex item properties.

## Requirements

- Stretch the layout to the full viewport (`html`, `body`, and `.container` at 100%) and use the flex main axis (row) to distribute the items.
- Experiment with `justify-content`, `align-items`, `flex-wrap`, `align-content`, and `gap` to explain how alignment works on both axes once wrapping kicks in.
- Configure individual items:
  - `.item-3` should grow to fill leftover space and use `flex: 1 5 300px`.
  - `.item-4` shrinks faster than the rest (`flex-shrink: 5`).
  - `.item-5` slides to the end of the main axis (`margin-left: auto`) and changes its cross-axis alignment.
  - Show how `align-self` and `order` can override the defaults for specific children.
