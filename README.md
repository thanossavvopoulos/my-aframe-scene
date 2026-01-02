# my-aframe-scene
# 3D Interactive Rubik's Cube (Space Christmas Edition)

A WebVR interactive application developed using the **A-Frame** framework for the Computer Graphics course. This project features a fully functional 3x3 Rubik's Cube simulation set in a festive space environment.

🔗 **Live Demo:** [Click here to view the scene](https://thanossavvopoulos.github.io/my-aframe-scene/)

## Features

* **Core Mechanics:** Full rotation logic for all slices (Up, Down, Left, Right, Front, Back).
* **Space Christmas Theme:** Custom environment combining a space skybox with a snowy terrain and holiday decorations.
* **Custom 3D Assets:** Includes custom `.glb` models (Christmas Trees, 3D Name Text) created in Tinkercad.
* **Interactive UI:** Modern "Glassmorphism" control panel for cube manipulation.
* **Game Logic:**
    *  **Shuffle:** Automated randomization algorithm.
    * **Animation Locking:** Prevents user input during animations to ensure geometric integrity.
* **Performance Monitoring:** Integrated stats (FPS, Draw Calls, Triangles) for better optimization analysis.

## Controls

The scene can be controlled via the on-screen menu or mouse interaction:

* **Menu Buttons:** Rotate specific slices of the cube.
* **SHUFFLE:** Randomizes the cube.
* **Mouse Drag:** Rotate the camera view.

## Technical Details

* **Framework:** [A-Frame v1.7.0](https://aframe.io/)
* **Languages:** HTML5, CSS3, JavaScript (ES6).
* **Assets:** glTF 2.0 (`.glb`) models from TinkerCad.

### Bonus / Experimentation
For the bonus part of the assignment, the standard cubelets were replaced with **High-Poly Candy Cane models**. This experiment demonstrated the impact of complex geometry on rendering performance (increased Draw Calls and Triangle count).

## Author

**Thanos Savvopoulos**
* **Course:** Computer Graphics
* **Department Of Informatics Ionian University**
