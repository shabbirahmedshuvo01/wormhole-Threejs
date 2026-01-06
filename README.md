# Wormhole Three.js

An interactive 3D wormhole tunnel visualization built with [Three.js](https://threejs.org/). This project is designed for learning and experimenting with advanced Three.js features, including custom geometry, camera animation, and post-processing effects.

## 🚀 Live Demo

[View the project live on Surge](https://wormhole-threejs.surge.sh/)

## Features

- Animated flythrough camera along a 3D spline tunnel
- Custom tunnel geometry using `TubeGeometry` and `CatmullRomCurve3`
- Dynamic wireframe and edge rendering
- Colorful, animated boxes distributed along the tunnel
- Post-processing with bloom effect for a glowing look
- Responsive to window resizing

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (for running a local server, optional)
- [Surge](https://surge.sh/) (for deployment, optional)

### Running Locally

1. **Clone or download this repository.**
2. **Serve the files using a static server.**
	- You can use [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) in VS Code, or run:
	  ```sh
	  npx serve .
	  ```
	- Or simply open `index.html` in your browser (may require a server for module imports).

### Project Structure

- `index.html` — Main HTML file
- `index.js` — Main Three.js scene and animation logic
- `spline.js` — Spline path data and curve creation
- `README.md` — Project documentation

### Main Concepts Used

- **Three.js Scene Setup:** Camera, renderer, controls, and fog
- **Spline Path:** Defined in `spline.js` using `CatmullRomCurve3`
- **Tube Geometry:** Creates a tunnel along the spline
- **Edges & Wireframes:** Visualizes geometry structure
- **Boxes:** Randomly placed and colored along the tunnel
- **Camera Animation:** Moves smoothly along the tunnel path
- **Post-processing:** Bloom effect for glowing visuals

## Deployment

This project is deployed using [Surge](https://surge.sh/):

1. Install Surge globally:
	```sh
	npm install --global surge
	```
2. Deploy from your project directory:
	```sh
	surge
	```
3. Enter your email, password, and domain (or use the suggested one).

## Learning Resources

- [Three.js Documentation](https://threejs.org/docs/)
- [Three.js Examples](https://threejs.org/examples/)
- [Three.js Journey](https://threejs-journey.com/) (premium)
- [Discover Three.js](https://discoverthreejs.com/)

## Credits

- Built with [Three.js](https://threejs.org/)
- Inspired by various tunnel and spline demos in the Three.js community

---

Happy learning and experimenting with Three.js!
