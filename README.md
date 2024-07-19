# cub3D Project

The cub3D project at 42 Network involves creating a 3D maze game using raycasting techniques, inspired by the classic game Wolfenstein 3D.

## Table of Contents

- [Project Overview](#project-overview)
- [Project Structure](#project-structure)
- [Usage](#usage)
- [Features](#features)
- [Controls](#controls)
- [Demo](#demo)
- [Contributing](#contributing)
- [License](#license)

## Project Overview

The main goal of the project is to create a basic 3D graphical representation of a maze using raycasting, where the player can navigate through the maze and interact with objects.

## Project Structure

The project typically consists of the following files:

- **cub3d.c**: Contains the main game loop and initialization of the game.
- **parse.c**: Functions for parsing and validating the configuration file (`.cub` file).
- **raycast.c**: Raycasting functions to render the 3D world using 2D projections.
- **texture.c**: Loading and applying textures to walls and sprites.
- **sprite.c**: Handling sprites in the game, including collision detection and rendering.
- **input.c**: Handling user input for player movement and interactions.
- **libft**: A library of utility functions (similar to the `libft` project) used throughout the game.
- **Makefile**: Defines compilation rules and dependencies for building the `cub3D` executable.

## Usage

To compile and run the `cub3D` program, follow these steps:

1. **Clone the repository:**

   ```bash
   git clone https://github.com/ehoussa/42-Cursus---cub3d/
   cd 42-Cursus---cub3d
   make
   ./cub3D path_to_configuration_file.cub

Replace path_to_configuration_file.cub with the path to your .cub configuration file containing the maze map and settings.


# Features

The cub3D program typically supports the following features:

    Raycasting Engine: Renders a 3D perspective of a maze using raycasting techniques.
    Wall Textures: Applies textures to walls based on configuration settings.
    Sprite Rendering: Displays sprites (e.g., items, enemies) in the game world.
    Player Movement: Allows the player to move within the maze and interact with objects.
    Minimap: Displays a top-down view of the maze with player position and orientation.

# Controls

The default controls for cub3D are typically as follows:

    W: Move forward
    A: Rotate left
    S: Move backward
    D: Rotate right
    Left Arrow: Strafe left
    Right Arrow: Strafe right
    Esc: Exit the game

Demo

Watch a demo of the cub3D project https://www.youtube.com/watch?v=0E5rE5p95Fo

This video demonstrates the functionality and gameplay of the cub3D project.
Contributing

Contributions are welcome! Please follow these steps to contribute:

    Fork the repository
    Create a new branch (git checkout -b feature/YourFeature)
    Commit your changes (git commit -am 'Add new feature')
    Push to the branch (git push origin feature/YourFeature)
    Create a new Pull Request

License

This project is licensed under the MIT License. See the LICENSE file for details.


This Markdown template provides a structured overview of the "cub3D" project, including its purpose, structure, usage instructions, features, controls, demo link, contribution guidelines, and licensing information. It also includes a placeholder for your project demo video link. Replace `https://www.youtube.com/watch?v=0E5rE5p95Fo` with your actual YouTube video link showcasing your cub3D project.










