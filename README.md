# Three.js Interactive Vertex Earth

Let's build an interactive globe with Three.js, complete with a starfield background and orbit controls. The globe uses custom shaders to apply textures, elevation, and alpha transparency.

## Features
- **Interactive Globe**: A rotating 3D globe built with an `IcosahedronGeometry`, wireframe, and point geometry using custom shaders.
- **Custom Shaders**: Vertex and fragment shaders are used for applying color, elevation, and alpha textures.
- **Starfield Background**: A dynamic starfield for added depth and visual appeal.
- **Orbit Controls**: Allows users to rotate and zoom the globe interactively using the mouse.
- **Responsive Design**: Automatically adjusts the canvas size when the window is resized.

### Customization
- **Globe Appearance**: Modify the textures in the `TextureLoader` (`colorMap`, `elevMap`, and `alphaMap`) to change the appearance of the globe.
- **Starfield**: Adjust the number of stars or their size in `getStarfield.js` to change the look of the starfield.
- **Shaders**: Modify the vertex or fragment shaders for custom visual effects on the globe's surface.

### Acknowledgments
- [Three.js](https://threejs.org/) for the awesome 3D library.
- [Three.js Forum](https://discourse.threejs.org/) for shader examples and discussions.

Watch the tutorial on [YouTube](https://youtu.be/XaDQI1HmoOQ)
