# Pitch Calculator

A simple calculator that gives you the pitch needed to hit a target, based on the range in studs.

## Formulas

| Range (R) | Formula |
|---|---|
| 0 to 450 | `P = 90 - R / 30` |
| 450 to 650 | `P = 75 - (R - 450) / 20` |
| Over 650 | `P = 65 - (R - 650) / 10` |

Turn on "Round the range for easier math" to round R to the nearest 30, 20, or 10 depending on the zone.

## Use it

Open `index.html` in any browser.

Credit to Wayward outpost and HolySmokeImTrash for this idea.
