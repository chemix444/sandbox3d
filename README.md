# Sandbox 3D

A physics sandbox game in your browser — spawn objects, grab them, build contraptions, and let physics do the rest. Built with Three.js and cannon-es.

**Play now:** `https://chemix444.github.io/sandbox3d`

## Features

- **40+ spawnable objects** — boxes, spheres, cylinders, torus knots, stairs, wedges, pipes, springs, spirals, and more
- **Real-time physics** — gravity, collisions, stacking, friction
- **4 tool modes** — Spawn, Grab, Delete, Clear
- **Full color picker** — spawn objects in any color
- **Wireframe mode** — toggle wireframe rendering
- **FPS counter** — monitor performance
- **Pointer lock controls** — WASD movement + mouse look like an FPS

## Controls

| Key | Action |
|-----|--------|
| WASD | Move |
| Mouse | Look around |
| Left click | Spawn / Grab / Delete (depends on mode) |
| Right click | Delete object under crosshair |
| G | Grab mode / Grab held object |
| F | Drop held object |
| R | Random color |
| C | Clear all objects |
| 1-4 | Switch tool mode |
| Esc | Release cursor |

## Tool Modes

- **Spawn** (1) — Click to place objects in the world
- **Grab** (2) — Click an object to pick it up; click again or press F to release
- **Delete** (3) — Click objects to remove them
- **Clear All** (4) — Remove every object at once

## Built With

- [Three.js](https://threejs.org/) — 3D rendering
- [cannon-es](https://pmndrs.github.io/cannon-es/) — Physics simulation
- [PointerLockControls](https://threejs.org/docs/#examples/en/controls/PointerLockControls) — FPS-style camera controls
