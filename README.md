# ELEMENTS: The Art of Bending — Prototype 0.1

This is Stage 1: a lightweight 3D/WebGL foundation with a third-person character, camera look, a training-ground environment, keyboard controls and mobile touch controls.

## Controls
- **Mobile:** left on-screen joystick moves; drag on the right side to rotate the camera.
- **PC:** WASD or arrow keys to move; hold Shift to run; drag with the mouse to look around.
- Designed for landscape orientation.

## Run and install
A PWA must be served from **HTTPS** (or localhost) to install and use its service worker. Opening `index.html` directly as a file lets you inspect the page in some browsers, but it will not enable PWA installation/offline caching.

### Easiest free route
1. Upload the contents of this folder to a static hosting service that provides HTTPS (for example, GitHub Pages).
2. Open the published HTTPS address in Chrome on Android.
3. Use Chrome's menu → **Install app** or **Add to Home screen**.
4. Open it from the new home-screen icon and rotate your phone to landscape.

No paid game subscription or game plugin is required. Hosting providers may change their free-tier terms.

## Current prototype limitations
- This is a first-pass 3D foundation, not the finished game.
- The character is a simple placeholder model.
- There are no bending abilities, enemies, missions, sound, or save progression yet.
- Landscape is requested by the PWA manifest; some browsers/devices may not enforce orientation lock.
- The world is rendered using native WebGL and has no external runtime library dependency.

## Feedback for version 0.2
Please test movement speed, camera sensitivity, character appearance, environment scale, and mobile controls. The next stage should only begin after the foundation is approved.
