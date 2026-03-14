# Canvas 3D Room Walkthrough

A self-contained 3D-style room demo implemented with the HTML5 Canvas 2D API (raycasting style). No build step and no local server are required.

## Run

1. Open `index.html` directly in your browser.
2. Click **Start** to lock the pointer.

## Controls

- **W / S** or **↑ / ↓**: move forward/back
- **A / D**: strafe left/right
- **← / →**: rotate (keyboard look)
- **Mouse**: look around while pointer is locked
- **← / →** always work for turning (fallback if pointer lock is blocked)
- **Esc**: unlock pointer

## Notes

- The room includes a desk/monitor area and distance-based lighting effects.
- Everything is in one file, so this works from `file://` without hosting.
- If pointer lock is blocked by browser policy, the game still starts and you can rotate with arrow keys.
