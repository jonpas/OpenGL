# FERI-OpenGL

OpenGL introduction application at Computer Graphics (slo. Računalniška Grafika).

### Features

- OpenGL Rendering in Qt with GLM
- Projections (Perspective and Orthogonal)
- Camera Translating and Rotating
- Object Translating, Rotating and Scaling
- Interleaved Vertex Buffer
- Loading OBJ Files Dynamically
- Multiple Objects Handling
  - Per-Model Buffers
- Texture Mapping
  - Simple (X, Y)
  - Planar (X, Y, Z)
  - Cylindrical (X, Y, Z)
  - Spherical (X, Y, Z)
- Blinn-Phong Shading/Reflection Model
  - Single Point Light
- Bump (Height) Mapping

**Controls:**
- Camera
  - Translation: <kbd>W</kbd> (Forward) / <kbd>A</kbd> (Left) / <kbd>S</kbd> (Backward) / <kbd>D</kbd> (Right) / <kbd>Q</kbd> (Up) / <kbd>E</kbd> (Down)
  - Rotation: <kbd>Right Mouse Button</kbd> + <kbd>Mouse Axis</kbd>
- Object
  - Translation: <kbd>H</kbd> (Left) / <kbd>J</kbd> (Forward) / <kbd>K</kbd> (Backward) / <kbd>L</kbd> (Right) / <kbd>U</kbd> (Up) / <kbd>N</kbd> (Down)
  - Rotation: <kbd>Y</kbd> (on Y) / <kbd>X</kbd> (on X) / <kbd>C</kbd> (on Z)
    - Negative Rotation: <kbd>Ctrl</kbd> + <kbd>Rotation Key</kbd>
  - Scale: <kbd>+</kbd> (Up) / <kbd>-</kbd> (Down)
- Projection Change: <kbd>P</kbd>

### Setup

**Dependencies:**
- [Qt](https://www.qt.io/)
- [OpenGL Mathematics (GLM)](https://glm.g-truc.net/)
