# MOTE

> Last spark in the dark.

A single-file HTML horde-survivor. You are a mote of light surrounded by the dark. Your weapons fire on their own — keep moving, level up, choose upgrades, see how long you can hold the dark back.

**▶ Play it:** https://cpv0310.github.io/mote/

## Controls

- **Move:** `WASD` / arrow keys — or drag the left half of the screen on touch devices
- **Pause:** `P` or `Esc`
- **Restart:** `R` from the game-over screen

Fire is automatic — every weapon aims itself.

## Weapons

Up to 4 weapons can be equipped at once. Each levels independently (5–6 levels each).

| Icon | Name | Behavior |
|------|------|----------|
| ✦ | **PULSE** | Starting weapon. Auto-fires motes at the nearest enemy. |
| ◯ | **ORBITERS** | Glowing orbs spin around you, damaging anything they touch. |
| ◉ | **NOVA** | Periodic radial shockwave damages everything around you. |
| ⚡ | **ARC** | Lightning chains from you between the nearest enemies. |
| ✜ | **SPEAR** | Piercing spears launch outward in a spinning fan. |

## Passives

`QUICKSILVER` (move speed), `VITALITY` (max HP + heal), `REGEN` (HP/s), `MAGNETISM` (pickup radius), `INSIGHT` (XP gain), `KNIFE EDGE` (crit), `RESILIENCE` (damage taken).

## Enemies

`shade` from t=0 · `rusher` from 1 min · `brute` from 2 min · `splitter` (spawns 2 babies on death) from 3 min. HP and damage scale with run time.

## Run locally

```sh
open index.html
```

Or any static server: `python3 -m http.server` then visit http://localhost:8000.

## Tech

Zero dependencies. Vanilla HTML + CSS + Canvas 2D. Single file (~870 lines).
