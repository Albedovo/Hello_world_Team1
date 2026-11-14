# Coffee Shop NYC

A comic-style rhythm café game for one or two players on one keyboard.

**[Play the latest version (V3)](https://albedovo.github.io/Hello_world_Team1/Coffee%20Shop%20NYC3.html)**

- [V3 — V2 + skippable tutorial, 8 / 3 minute shifts](https://albedovo.github.io/Hello_world_Team1/Coffee%20Shop%20NYC3.html)
- [V2 — two counters and shared orders](https://albedovo.github.io/Hello_world_Team1/Coffee%20Shop%20NYC%20v2.html)
- [V1 — original version (unchanged)](https://albedovo.github.io/Hello_world_Team1/Coffee%20Shop%20NYC.html)

## Version History

| Version | File | Shift length | Highlights |
| --- | --- | --- | --- |
| V1 | `Coffee Shop NYC.html` | 10 min full day / 4 min quick | First playable build: kitchen with a central island, NYC street through the window, afternoon → night |
| V2 | `Coffee Shop NYC v2.html` | 10 min full day / 4 min quick | Two parallel counters, shared order board, numbered and color-coded stations |
| V3 | `Coffee Shop NYC3.html` | **8 min** full day / **3 min** quick | Everything in V2, plus an interactive tutorial that players can skip |

## V3

V3 is V2 with only two changes. The layout, art, recipes, controls and hints are the same as V2.

- **Shorter shifts.** FULL DAY is now **8 minutes** (4 min afternoon + 4 min night). QUICK SHIFT is now **3 minutes**, with sunset in the middle. The title screen, the training page and the clock show the new times.
- **Interactive tutorial.** Press **OPEN SHOP!** (or Space / Enter) on the Barista Training page to start a short hands-on lesson with Mo, the manager. The lesson uses V2's station numbers, so players can follow the bouncing arrow or just read the numbers:
  1. **Iced Americano for Mia:** 02 ICED CUP → 07 ICE → 03 ESPRESSO ×2 → 04 WATER (hold, release in the green zone) → serve at WINDOW 3.
  2. **Toasted Bagel for Leo:** 11 BAGEL → 12 OVEN → take it out before it burns → serve at WINDOW 4.
  3. Press Space to open the shop and start the real shift.
- **Skippable.** The first tutorial card has **SKIP → OPEN SHOP**. Every later step has **SKIP TUTORIAL**, and **Esc** skips at any time.
- During the tutorial the clock doesn't run, customers keep their patience, and no random customers arrive. Arrows always show unless H turns them off. It works for 1 or 2 baristas.

## V1 — Original

The first complete build of Coffee Shop NYC. It is kept unchanged for comparison.

- **Comic flat-illustration café** with a large window onto a NYC street: brownstones, shop awnings (bodega, books, laundry, pizza, flowers, records), yellow cabs and pedestrians.
- **Afternoon → night:** the street fades from GOLDEN HOUR to NIGHT IN MANHATTAN halfway through the shift. The synth music speeds up for the last call in the final 30 seconds.
- **Shift length:** FULL DAY 10 min (5 afternoon + 5 night) or QUICK SHIFT 4 min. Press L on the title screen to switch.
- **Kitchen:** a single room with a central island of espresso machines and the frother. Cups, pastries, water, milk, syrups, ice, ovens and the trash sit around the walls.
- **Menu:** Double Espresso, Americano, Latte, Cappuccino, Mocha, Vanilla Latte, Iced Latte, Iced Caramel, Iced Americano, Toasted Bagel and Warm Croissant. Simple drinks come first; mochas and espressos show up more at night.
- **Rhythm mechanics:** tap on the beat for PERFECT shots and bigger tips. Stop pours in the green zone for PERFECT POUR. Froth to FLUFFY FOAM. Pastries go TOASTY! but can end up BURNT!
- **Help:** a Barista Training page explains the steps. A bouncing arrow and bottom hints guide new players (H toggles hints).
- 1 or 2 baristas on one keyboard. The tip jar, combo and stars count toward the final score.

## V2

- Two parallel counters and two open walking lanes; no central island.
- Bagels and croissants sit next to the ovens.
- Arrows show **TAP / HOLD + the actual key** during the first 60 seconds of each shift and for recipes you have never successfully served. Delivery arrows point above customers; bottom guidance remains available for the whole game. First-time completion is saved in this browser (session-only if storage is unavailable).
- A shared order board shows drink names, remaining steps, ingredient counts, and ready-to-serve orders. Cards sort by seconds of patience remaining, most urgent first, and retain their window numbers.
- Each customer has random patience, with extra time for complex orders and the opening customers.
- Machine counters, labels, order bubbles, and recipe steps share the same **station number, name, and color**. Completed steps keep their machine color and gain a checkmark.
- Co-op has no assigned roles or customers. Either barista can start or continue any item.

| Player | Move | Take / put / serve | Use machine / pour |
| --- | --- | --- | --- |
| 1P | WASD | C (or Space) | V |
| 2P | Arrow keys | K (or Enter) | L |

Tap the machine key to brew, pump syrup, froth, or add ice. Hold it to pour milk/water; release in the green zone. At the espresso machine, put a cup down, tap to brew, then pick it up. Pastries bake automatically in the oven. Esc pauses, M mutes, and H toggles arrows; after the first minute only never-served recipes keep world guidance. Co-op tutorials are shared by the team. Bottom guidance stays visible. Solo also accepts the second player's controls.

Open either game HTML directly in a desktop browser; no install or build step is needed. Google Fonts loads when online; local fallback fonts work offline.

## Files and Pages

- `Coffee Shop NYC.html`: V1, preserved original game.
- `Coffee Shop NYC v2.html`: V2.
- `Coffee Shop NYC3.html`: V3, V2 + skippable tutorial and 8 / 3 minute shifts.
- `index.html`: root entry that opens V3 with a relative URL, including under the GitHub Pages repository path.
- `references/`: the four original PNG reference images, unchanged.
- `.nojekyll`: serves this buildless static project directly.

GitHub Pages: deploy from the **main** branch and **/ (root)**. The repository URL shows source; the **Play** link above opens the game.
