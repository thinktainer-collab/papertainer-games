# Papertainer Games

A small game studio, currently in beta testing. Browser games you can play instantly at
[games.papertainer.com](https://games.papertainer.com).

## Games

- **좀비 미로 탈출 (Zombie Maze Escape)** — `zombie-maze/`
  3D first-person mobile game. Episode 1: find four keys and escape the maze.
  Episode 2: a chase through a larger maze and zombie hordes.
  Episode 3: a bigger mecha, a five-boss battle and a very fast two-phase zombie.
- **뿡뿡 랠리 (Ppung Ppung Rally)** — `ppung-rally/`
  2D off-road racing (canvas). Fart-boost overtakes, hills and jump ramps,
  three courses that rotate endlessly, garage upgrades. No ending yet.
  Source and later 3D work live in the papertainer repo under `ppung-rally/`.

## Structure

Each game lives in its own folder and is plain static files (no build step).
`zombie-maze/game/three.module.min.js` is three.js (MIT, see `three.LICENSE`).
