# Avalanche Run

A top-down ski game in a single HTML file — no build step, no dependencies. Open `index.html` in a browser.

You ski down an endless, procedurally generated mountain while an avalanche chases you. It speeds up the
further you go, and every crash costs you speed. Three hearts; if you lose them all, or the avalanche
catches you, the run is over.

## Controls

| Key | Action |
| --- | --- |
| `←` `→` / `A` `D` | Steer (straight down is fastest, sideways is slow) |
| `↓` / `S` | Tuck: +30% speed, wider turns |
| `↑` / `W` | Brake: sharper turns, much slower |
| `Space` (hold, in the air) | Spin; `←`/`→` picks direction. Release in time to land clean |
| `P` / `Esc` | Pause |
| `M` | Mute |

Touch devices get on-screen buttons.

## What's in it

- **Obstacles:** pines, dead trees, rocks, logs, stumps, moving snowboarders
- **Terrain:** moguls (small pops), ice patches (no grip), ramps
- **Scoring:** distance + slalom gates (centre = perfect), close calls, trick landings, big air; a combo multiplier
  rewards chaining them and a crash resets it
- **Pickups:** cocoa (+1 heart), hot wax (speed boost)
- **Biomes:** Pine Forest → Alpine Ridge (1,200 m) → Glacier (3,000 m), with difficulty ramping throughout
- **Tricks are risky:** a 360 is easy, a 720 needs a precise release, and landing mid-spin wipes you out
