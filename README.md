# SON CAR RACING — 3D Highway Racer

A browser-based 3D arcade racing game built with **HTML, CSS, JavaScript and Three.js**. It features a chase camera, procedural 3D cars, traffic, a highway environment, speed/score HUD, nitro boost, keyboard and touch controls, and local best-score storage.

## Play locally

1. Save `son-car-racing.html`.
2. Open it in a current browser while connected to the internet.

The game imports Three.js from jsDelivr, so an internet connection is needed. Some browsers restrict ES modules when opened as a local file. If it does not start, use a local server:

```bash
python -m http.server 8000
```

Then open:

```text
http://localhost:8000/son-car-racing.html
```

## Controls

| Action | Keyboard | Touch |
|---|---|---|
| Steer left/right | Left/Right arrows or A/D | Left/right buttons |
| Accelerate | W or Up arrow | Gas button |
| Brake | S or Down arrow | Brake button |
| Nitro | Shift or Space | Lightning button |
| Pause/resume | P or Esc | Pause button |
| Start | Enter or Start button | Start button |

## Features

- Third-person 3D chase camera
- Procedurally modeled player car and traffic vehicles
- Highway, lane markings, guardrails, city buildings, trees and streetlights
- Traffic collision and race-over screen
- Speed, distance, score and best score display
- Nitro boost and performance/high graphics toggle
- Responsive mobile touch controls
- Best score saved in browser local storage

## Technology

- HTML5
- CSS3
- JavaScript ES modules
- [Three.js](https://threejs.org/) for 3D rendering
- WebGL

## Notes

This is a playable **3D arcade prototype**, not a full photorealistic driving simulator. The cars and environment are generated from 3D shapes, and the game uses simplified arcade physics. For a higher-fidelity simulator, add licensed 3D vehicle/environment assets, engine and tire audio, more advanced vehicle physics, and optimized lighting/shadows.

## Project structure

```text
son-car-racing/
├── son-car-racing.html
└── README.md
```

## Customization

Open `son-car-racing.html` in a code editor. You can adjust car colors, road dimensions, traffic speed, lighting, camera position, and HUD styling in the JavaScript and CSS sections.

## License

No license has been specified. Choose and add a license before redistributing the project.
