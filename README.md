# Obstacle Avoidance Simulator

**Browser-based robot navigation and obstacle avoidance demo**

Live demo: https://aaronjs99.github.io/obstacle-avoidance-simulator/

---

## Overview

This repository contains a browser-based 2D robot navigation simulator implementing basic obstacle avoidance and path planning logic. The project was built as an early exploration of geometric reasoning, collision handling, and motion planning concepts, implemented entirely in JavaScript and rendered in HTML.

The simulator allows a user-controlled agent to navigate a planar environment populated with obstacles, demonstrating simple planning and avoidance behavior in real time.

This project is preserved as an interactive visualization and educational prototype. It is not intended to be a full robotics framework or a production-grade planner.

---

## Features

- 2D robot motion in a planar workspace
- Obstacle avoidance using geometric reflection and collision handling
- Basic path planning logic
- Real-time interaction via keyboard and mouse input
- Fully client-side implementation (no backend)

---

## Implementation Notes

The simulator is implemented using plain JavaScript, HTML, and CSS, without external libraries. The code is organized into small modules handling:

- Environment and agent state
- Path planning logic
- Keyboard and mouse interaction
- Rendering and visualization

The focus of the project is conceptual clarity and interactivity rather than algorithmic optimality or performance.

---

## Repository Structure

- **index.html**  
  Entry point and main simulation canvas

- **js/**  
  Core simulation and planning logic
  - `gameClass.js` – environment and agent representation  
  - `pathPlan.js` – basic path planning logic  
  - `gameFunctions.js` – simulation utilities  
  - `keyboardShortcuts.js`, `mouseShortcuts.js` – user interaction

- **css/**  
  Styling for the simulation interface

- **images/**  
  UI assets and control references

---

## Status

This is a **completed prototype** and is no longer under active development.  
The repository remains public as a reference and demonstration of early work in robot navigation and planning visualization.

---

## License

This project is released under the **GPL-2.0 license**.  
See the `LICENSE` file for details.

---

## Author

Aaron John Sabu

---

