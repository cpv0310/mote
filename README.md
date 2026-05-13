# MOTE

> Last spark in the dark.

A single-file HTML horde-survivor. You're a mote of light. Auto-fires at the nearest threat. Survive as long as you can, collect XP, pick upgrades, hold back the dark.

**▶ Play it:** https://cpv0310.github.io/mote/

## Controls

- **Move:** `WASD` / arrow keys — or drag the left half of the screen on touch devices
- **Pause:** `P` or `Esc`
- **Restart:** `R` from the game-over screen

Auto-fires at the closest enemy — no fire button.

## What's in it

- 4 enemy types unlocked by run time: `shade` (basic) → `rusher` (fast) → `brute` (tanky) → `splitter` (spawns 2 babies on death)
- 11 stackable upgrades — damage, fire rate, +projectiles, pierce, move speed, max HP, regen, magnet radius, XP gain, crit, range
- Persistent best run via `localStorage`
- Zero dependencies, single file, ~680 lines of HTML/CSS/JS

## Run locally

```sh
open index.html
```

Or any static server: `python3 -m http.server` then visit http://localhost:8000.
