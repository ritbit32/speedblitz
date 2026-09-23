# SpeedBlitz

A low-poly arcade spaceship dogfighting game built in Unreal Engine 5, focused on making speed *feel* visceral — camera lag, FOV shifts, motion blur, and Niagara VFX all work together to sell velocity over realism.

![Engine](https://img.shields.io/badge/Engine-Unreal%20Engine%205-313131?logo=unrealengine)
![Status](https://img.shields.io/badge/Status-In%20Development-yellow)
![Genre](https://img.shields.io/badge/Genre-Arcade%20Dogfighting-blueviolet)

---

## Overview

SpeedBlitz puts you in the cockpit of a nimble low-poly fighter, third-person camera trailing just behind as you weave through combat. The design goal isn't flight-sim realism — it's the exaggerated, weighty rush of arcade dogfighting, where every bank, dive, and volley feels immediate and physical.

## Features

- **Mouse-driven flight steering** — yaw follows the mouse directly, WASD/arrow keys handle pitch and throttle, with automatic banking on turns for that fighter-jet lean
- **Camera lag & rotation lag** — the chase camera trails the ship's motion instead of snapping rigidly, reinforcing a sense of speed and inertia
- **Twin-mounted laser cannons** — dual wingtip emitters fire in sync, converging on a camera-driven aim trace so shots land where the crosshair points, not just where the guns are mounted
- **Dynamic crosshair** — HUD reticle reflects the ship's live aim direction
- **Zero-gravity projectile physics** — no bullet drop, true-to-space laser trajectories
- **Niagara-powered VFX** — thruster trails, impact effects, and speed-driven particle work
- **Motion blur & FOV shifting** — camera effects scale with velocity to amplify the feeling of speed during boosts and sharp maneuvers

## Controls

| Input | Action |
|---|---|
| `W A S D` | Directional flight / throttle |
| `Mouse` | Steer (yaw) |
| `↑ / ↓` | Pitch |
| `A / D` (hold while turning) | Automatic banking |
| `Left Mouse Button` | Fire lasers (hold for continuous fire) |

## Tech Stack

- **Engine:** Unreal Engine 5
- **Scripting:** Blueprints (Enhanced Input System)
- **VFX:** Niagara
- **Art style:** Low-poly, stylized

## Roadmap

- [ ] Enemy AI and combat encounters
- [ ] Scoring / mission structure
- [ ] Additional ship variants
- [ ] Polish pass on VFX and camera feel
- [ ] Audio (engine hum, weapon fire, impacts)

## Getting Started

1. Clone the repository
2. Open the project in **Unreal Engine 5**
3. Open `NewMap` (or the current default level) and hit **Play**

```bash
git clone https://github.com/<your-username>/speedblitz.git
```

## Development Log

This project is under active development. Core flight and weapon systems are functional; combat, progression, and polish are in progress.

## License

*Add your chosen license here (e.g. MIT).*

## Author

Built by **Ritunjay Kushwaha** ([@ritbit32](https://github.com/ritbit32))
