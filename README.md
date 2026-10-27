# Keyline maker

Enter a carton's inside size (length × breadth × height, in mm) and get its keyline: cut and fold lines, ready to download as a true-scale PDF or SVG.

## Supported styles

- Slotted carton with four top and four bottom flaps and a glued side seam.

## Construction rules

- Top and bottom flaps are half the breadth (plus an optional overlap, default 0 mm).
- Glue flap is 45 mm by default and tapers at 15°.
- Side-panel folds sit 2 mm inside the long-panel folds.
- The last side panel is 1 mm narrower than the breadth.
- Slots between flaps are 6 mm wide with rounded ends.

Board thickness is not taken into account.

## Running it

It's a single static file. Open `index.html` in a browser, or host it with GitHub Pages.
