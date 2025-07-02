# threejs-solar-system

A 3D animation of a simplified solar system using Three.js. Includes a rotating sun, an orbiting earth, and a moon that orbits the earth. Demonstrates object hierarchies, time-based animations, and texture-mapped meshes.

---

## Overview

This project visualizes a miniature solar system:

- The **sun** rotates and emits light.
- The **earth** orbits the sun and spins on its axis.
- The **moon** orbits the earth.

---

## Technologies Stack

- Three.js
- JavaScript / HTML
- OrbitControls (camera interaction)
- TextureLoader (for applying images to meshes)

---

## Files

- `solor-system.html`: Main scene and animation logic
- `sun.jpg`, `earth.jpg`, `moon.jpg`: Texture maps for bodies
- `presentation.mp4`: demo video

---

## Demo

[▶️ Watch the demo](/threejs-solar-system/presentation.mp4)

---

## Features

- Nested group motion for realistic orbits
- Independent spin and orbit animations
- Elliptical paths using `THREE.EllipseCurve`
- Emissive sun with `MeshStandardMaterial`
- Texture-mapped planets and moon
- Interactive camera controls via `OrbitControls`

---

## Running the Code

Open `solor-system.html` in a modern browser (no server required).

---

## Future Improvements

- Add more planets with unique orbits

---

## License

MIT License
