# Avalanche Run

A third-person ski game (camera behind the skier, looking down the slope) in a single HTML file — no build step, no dependencies. Open `index.html` in a browser.

You ski down an endless, procedurally generated mountain. Obstacles are solid: hit one and you stop, tumble and
lose a heart. An avalanche chases from behind. It is slower than clean skiing, so a good run pulls away and can
go on indefinitely, but crashes and stalls let it catch up. Three hearts; lose them all or get caught and it's over.

## Controls

| Key | Action |
| --- | --- |
| `←` `→` / `A` `D` | Steer (straight down is fastest, sideways is slow) |
| `↑` / `W` | Speed up (tuck): +30% speed, wider turns |
| `↓` / `S` | Brake: sharper turns, much slower |
| `Space` (tap, on the ground) | Hop low obstacles: logs, rocks, stumps (never trees) |
| `Space` (hold, in the air) | Spin; `←`/`→` picks direction. Release in time to land clean |
| `P` / `Esc` | Pause |
| `M` | Mute |

Touch devices get on-screen buttons (the right-hand ones are hop/trick, brake and speed).

Pick **Chill / Normal / Hard** on the title or game-over card. It changes obstacle density, how wide the clear line
is, avalanche speed and how many snowboarders cross the slope. Your choice and a best score per level are saved.

## What's in it

- **Obstacles:** pines, dead trees, rocks, logs, stumps, moving snowboarders
- **Terrain:** moguls (small pops), ice patches (no grip), ramps
- **Scoring:** distance + slalom gates (centre = perfect), close calls, trick landings, big air; a combo multiplier
  rewards chaining them and a crash resets it
- **Pickups:** cocoa (+1 heart), hot wax (speed boost)
- **Biomes:** Pine Forest → Alpine Ridge (1,200 m) → Glacier (3,000 m), with difficulty ramping throughout
- **Tricks are risky:** a 360 is easy, a 720 needs a precise release, and landing mid-spin wipes you out
