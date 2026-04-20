# prj-brick-breaker

A fast-paced, responsive Brick Breaker game built with HTML5 Canvas and Vanilla JavaScript. This project focuses on real-time physics, collision detection, and cross-device input handling.

**[Live Demo Link](https://otvnvs.github.io/prj-brick-breaker-js)**

## Features
- **Mobile First:** Optimized for touchscreens with fluid finger-tracking controls.
- **Dynamic Physics:** Real-time ball-to-paddle and ball-to-brick collision logic.
- **Score System:** Tracks points as you clear the board.
- **Responsive Canvas:** Scales the game view for both desktop and mobile browsers.

## Tech Stack
- **HTML5 Canvas:** For high-performance 2D rendering.
- **JavaScript (ES6):** Game loop architecture and coordinate geometry.
- **CSS3:** Flexbox-based centering and dark-mode styling.

## Technical Highlights
- **Touch Event Mapping:** Uses `touchmove` events with coordinate scaling to ensure the paddle follows your finger exactly, regardless of screen size.
- **Collision Matrices:** Implements a 2D array system to track brick status and trigger physics reversals.
- **RequestAnimationFrame:** Utilizes the browser's native animation API for smooth 60FPS gameplay.

## How to Run Locally
1. Clone the repository:
   ```bash
   git clone https://github.com
   ```
