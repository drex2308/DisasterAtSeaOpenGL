# Disaster at Sea

## Overview

This repository contains the implementation of a computer graphics project titled "Disaster at Sea." The primary goal of this project was to demonstrate the use of OpenGL for creating graphical applications, focusing on rendering scenes, implementing textures, and handling user interactions through keyboard and mouse inputs.

## Description

The "Disaster at Sea" project simulates a scenario where a ship encounters various obstacles at sea. The user can interact with the scene to trigger different events such as collisions and avoidances. The project utilizes OpenGL to render the scenes and handle transformations.

## Features

### Scene Interactions
- **Sailing Ship**: The initial scene shows a ship sailing from left to right on the sea.
- **Collision**: Users can trigger a collision event where the ship collides with a rock and sinks.
- **Avoidance**: Users can trigger an avoidance event where the ship successfully avoids the rock.
- **Speed Control**: Users can increase or decrease the speed of the ship.
- **Day/Night Mode**: Users can switch between day and night scenes.

### Implementation Details
- **OpenGL Functions**: Utilizes various OpenGL functions such as `glutInit()`, `glutCreateWindow()`, `glutDisplayFunc()`, `glutMainLoop()`, and more for window creation, display management, and event handling.
- **User-Defined Functions**: Includes custom functions for rendering the ship, rock, water, and handling different scene modes (day/night, collision/avoidance).
- **Keyboard and Mouse Inputs**: Implements keyboard and mouse input handling to allow users to interact with the scene and trigger events.

## Usage

To run the "Disaster at Sea" project:
1. Ensure you have OpenGL and GLUT installed on your system.
2. Compile the provided source code using an appropriate C compiler.
3. Run the compiled program to start the simulation.
4. Use the keyboard and mouse inputs to interact with the scene:
   - **C/c**: Trigger collision event.
   - **A/a**: Trigger avoidance event.
   - **W/w**: Increase ship speed.
   - **S/s**: Decrease ship speed.
   - **D/d**: Switch to day mode.
   - **N/n**: Switch to night mode.
   - **Q/q**: Quit the simulation.

## Learnings

- **OpenGL Programming**: Gained experience in using OpenGL for rendering 2D graphics and handling user interactions.
- **Graphics Transformations**: Learned to apply transformations such as translation, rotation, and scaling to graphical objects.
- **Event Handling**: Implemented keyboard and mouse event handling to create interactive graphics applications.
- **Scene Management**: Developed skills in managing and switching between different scenes based on user inputs.

## Conclusion

This project was a valuable experience in developing a graphical application using OpenGL. The "Disaster at Sea" simulation demonstrates the ability to create interactive and visually appealing scenes, showcasing the power of OpenGL for computer graphics.
