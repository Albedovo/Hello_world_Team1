# Coffee Shop NYC

A comic-style rhythm café game for one or two players on one keyboard.

**[Play the latest version](https://albedovo.github.io/Hello_world_Team1/)**

- [V2 — two counters and shared orders](https://albedovo.github.io/Hello_world_Team1/Coffee%20Shop%20NYC%20v2.html)
- [Original version (unchanged)](https://albedovo.github.io/Hello_world_Team1/Coffee%20Shop%20NYC.html)

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

- `Coffee Shop NYC.html`: preserved original game.
- `Coffee Shop NYC v2.html`: new version.
- `index.html`: root entry that opens V2 with a relative URL, including under the GitHub Pages repository path.
- `references/`: the four original PNG reference images, unchanged.
- `.nojekyll`: serves this buildless static project directly.

GitHub Pages: deploy from the **main** branch and **/ (root)**. The repository URL shows source; the **Play** link above opens the game.
