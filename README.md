# Super Bo

A 1990s-style arcade football brawler that runs in the browser. Bo, #34, takes the handoff and runs a booby-trapped field. When a defender gets his hands on him, the game cuts to a side-on street fight.

**Play it:** open `index.html` in any browser, or visit the GitHub Pages link for this repo.

## How to play

- **Downs:** 4 tries to gain 10 yards. Fail and the game is over.
- **Scoring:** ½ point per yard, 3 per coin, 2 per defender beaten, +5 bonus for every knockout.
- **The Enforcer:** the one purple jersey in the game starts a street fight on contact. Anyone else tackles you, unless you press **Z** to pick a fight first.
- **Blue lightning:** one per game. An earthquake splits the field and Bo gets a clear road to the end zone.

### Controls

| Running | Street fight |
| --- | --- |
| ← → steer | ← → move, ↑ jump, ↓ block |
| Space: hurdle | A: karate kick |
| A: spin, W: flip | D: ball and chain |
| D: bat chop | S: katana |
| Z: pick a fight | W: home run (opponent under 25%) |

P or Esc pauses. On a phone, everything has an on-screen button.

## Tech

One self-contained HTML file: plain JavaScript and the Canvas 2D API, with no build step and no dependencies. Fonts load from Google Fonts. Sound effects are generated live with the Web Audio API.
