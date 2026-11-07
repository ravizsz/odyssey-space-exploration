# ODYSSEY — Space Exploration

A self-contained interactive space exploration game. Pilot the Wayfarer, navigate the fictional Odyssey-7 system, discover worlds, scan celestial bodies and complete missions.

## Features
- Animated starfield and interactive orbital system map
- Six celestial bodies with individual descriptions and properties
- Click-to-select worlds, zoom, drag-to-pan and orbit visualization
- Spacecraft flight controls, thrust, velocity, fuel and stabilization
- Planetary scanning, discovery codex and mission progression
- Three objectives: First Contact, Blue Horizon and Outer Reach
- Responsive interface, mission archive and flight manual
- No API keys, backend, database or external 3D engine required

## Requirements
Node.js 18+ and npm.

## Run locally
```bash
npm install
npm run dev
```
Open the local URL printed by Vite, normally http://localhost:5173.

## Production build
```bash
npm run build
npm run preview
```
The production bundle is generated in `dist/`.

## Controls
| Input | Action |
|---|---|
| W / ↑ | Increase thrust |
| S / ↓ | Reduce velocity |
| A / ← | Adjust heading |
| D / → | Adjust heading |
| Space | Brake / stabilize |
| Drag | Rotate / pan system map |
| Mouse wheel | Zoom |
| Click a world | Select celestial body |

Select a world, use **SCAN** to add it to the codex, and **INITIATE APPROACH** to establish orbit and progress missions.

## Project structure
```text
odyssey-space-exploration/
├── index.html
├── package.json
├── vite.config.js
├── .gitignore
├── README.md
├── LICENSE
└── src/
    ├── main.js
    └── style.css
```

## Technology
Vite, vanilla JavaScript, HTML, CSS and Canvas 2D.

## Scientific note
ODYSSEY is an interactive game and visualization, not a scientifically accurate orbital simulator. Odyssey-7 and its planetary data are fictional game content.

## License
MIT. See [LICENSE](./LICENSE).
