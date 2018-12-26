# FERI-OpenGL

OpenGL introduction application at Computer Graphics (slo. Računalniška Grafika).

### Features

- OpenGL Rendering
- Projections (Perspective and Orthogonal)
- Camera Translating and Rotating
- Object Translating, Rotating and Scaling
- Interleaved Buffering
- Loading OBJ Files (TODO)
- Multiple Objects Handling (TODO)
- Textures (TODO)
- Blinn-Phong Shading/Reflection Model (TODO)
- Bump Mapping (TODO)

**Controls:**
- Camera
  - Translation: <kbd>W</kbd> (Forward) / <kbd>A</kbd> (Left) / <kbd>S</kbd> (Backward) / <kbd>D</kbd> (Right) / <kbd>Q</kbd> (Up) / <kbd>E</kbd> (Down)
  - Rotation: <kbd>Right Mouse Button</kbd> + <kbd>Mouse Axis</kbd>
- Object
  - Translation: <kbd>H</kbd> (Left) / <kbd>J</kbd> (Forward) / <kbd>K</kbd> (Backward) / <kbd>L</kbd> (Right) / <kbd>U</kbd> (Up) / <kbd>N</kbd> (Down)
  - Rotation: <kbd>Y</kbd> (Rotate on Y) / <kbd>X</kbd> (Rotate on X) / <kbd>C</kbd> (Rotate on Z)
    - Opposite Rotation: <kbd>Ctrl</kbd> + Rotation Key
  - Scale: <kbd>+</kbd> (Scale Up) / <kbd>-</kbd> (Scale Down)
- Projection Change: <kbd>P</kbd>

### Setup

**Dependencies:**
- [Qt](https://www.qt.io/)
- [OpenGL Mathematics (GLM)](https://glm.g-truc.net/)