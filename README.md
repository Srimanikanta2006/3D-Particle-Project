# 3D-Particle-Project
This project is a browser-based 3D particle playground built with Three.js and MediaPipe Hands.
Your webcam tracks both hands in real time and drives a reactive 3D particle cloud that morphs into different shapes and responds to your gestures.
Everything (HTML, CSS, JS) lives in a single index.html file. No build tools or bundlers required.

Controls & Gestures
Right hand – shape selection
1 finger up
→ Particles form a heart.
2 fingers up
→ Particles form a smiley face:
Tight circle outline.
Compact eyes.
Clear U‑shaped mouth opening upwards.
3 fingers up
→ Particles form Saturn:
Dense spherical planet.
Thin, tilted ring around it.
Other poses (0, 4, random)
→ Particles form a swirling energy field:
Vortex/column of particles around your hands.
Animated swirl that evolves over time.
Left hand – zoom
Closed fist → Zoom in (bigger, closer cluster).
Open palm → Zoom out (smaller, further cluster).
Both hands can be used simultaneously:
Right hand picks the shape; left hand zooms it.
UI elements
Color picker:
Top-right panel → “Particle colour”.
Drag or pick a new color and all particles update instantly.
Status text:
Shows what the app is doing (initializing, camera active, tracking hints, or error messages).

**Technology Stack**
_Three.js (from CDN)_
  Rendering, camera, scene, points material, and animation loop.
_MediaPipe Hands (from CDN)_
  Real-time hand landmarks and handedness detection.
_Plain JavaScript, HTML, CSS_
  Single-file implementation (index.html).
  No frameworks or build tools.
