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

## Progression

Everything you do earns **coins**, and the shop turns them into upgrades and looks.

- **Earning:** coins sit along the open line, float over logs (hop for them) and arc along ramp jumps. After a run you also
  get coins for distance, gates, tricks, close calls, completed missions and a daily-streak bonus. Hard pays ×1.5.
- **Missions:** three at a time, each worth coins. Finish one and it is replaced by a new one.
- **Skier level:** your score is XP. Each level-up pays a coin bonus.
- **Records:** once you have a best distance, a banner is placed across the lane at that distance. Beat it for a bonus.
- **Upgrades (9):** Coin Magnet, Premium Wax, Combo Keeper, Thermos, Sharp Edges, Gold Digger, Score Boost, Cold Snap,
  Tough Skin (extra hearts).
- **Looks:** six jackets and five ski trails (including a rainbow one). Cosmetics change nothing about gameplay.

Progress is saved in your browser (`localStorage`). There is a **Reset progress** link at the bottom of the shop.
