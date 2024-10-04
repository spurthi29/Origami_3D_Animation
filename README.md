# Origami_3D_Animation

## Project Overview

This project is a 3D animation of a paper boat created using OpenGL and GLUT (OpenGL Utility Toolkit). The animation showcases the folding and unfolding dynamics of the boat, simulating an origami experience through real-time graphics. The project demonstrates the capabilities of 3D graphics programming, including geometric transformations, color management, and user interaction.

## Features

- **3D Visualization**: Utilizes OpenGL to render a 3D representation of a paper boat.
- **User Interaction**: Allows users to manipulate the animation using keyboard inputs to control rotations and transitions.
- **Dynamic Animation**: Implements smooth transitions and realistic folding animations to mimic origami techniques.
- **Customizable Parameters**: Users can modify the angles and states of the animation, providing a customizable experience.

## Technologies Used

- **Programming Language**: C
- **Graphics Library**: OpenGL
- **Windowing Toolkit**: GLUT

## Installation

To run this project, ensure you have the following installed:

1. **C Compiler**: GCC or any standard C compiler.
2. **OpenGL**: Ensure you have OpenGL libraries installed on your system.
3. **GLUT**: Install the GLUT library for window management and input handling.

### Steps to Compile and Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/origami-3d-animation.git
   cd origami-3d-animation
   ```

2. Compile the code:
   ```bash
   gcc -o origami origami.c -lGL -lGLU -lglut
   ```

3. Run the executable:
   ```bash
   ./origami
   ```

## Controls

- Press `i`, `j`, `k` to rotate the origami boat in different directions.
- Press `z` to initialize the animation.

## Code Explanation

The code consists of several key components:

- **Global Variables**: Variables are defined to manage the state of the animation, including angles, translation values, and flags for different stages of the animation.

- **Drawing Functions**: Functions such as `drawtriangleone`, `drawtriangletwo`, etc., are responsible for rendering different parts of the boat and managing their transformations.

- **Animation Logic**: The `display` function handles the main animation loop, where the current state of the animation is updated and rendered.

- **User Input Handling**: The `keys` function manages keyboard inputs to control the animation's behavior in real-time.

## Future Improvements

- Add more intricate origami shapes and animations.
- Improve the user interface for better interaction.
- Include sound effects and background music to enhance the experience.


[Practical Implementation](https://github.com/user-attachments/assets/4bbff6c7-bc3b-4bf6-b281-e66299f63959)
