# WorldBuilding

## Partners
- Andy Dinh
- Luke Li
- Isaac Lucero

## Overview
The "Build Your Own World" project is a Java program that allows users to generate and explore custom game worlds. The program uses procedural generation techniques to create unique game environments, including rooms, hallways, and walls. Users can interact with the world through keyboard inputs or input strings.

## Files

### 1. `Main.java`
- This file contains the main entry point for the program.
- It parses command-line inputs and delegates control to the `Engine` class.

### 2. `Engine.java`
- The `Engine` class handles user interactions and game logic.
- It includes methods for keyboard-based gameplay, input string processing, and world generation.

### 3. `WorldGenerator.java`
- The `WorldGenerator` class is responsible for generating the game world.
- It utilizes random generation algorithms to create rooms, hallways, and walls within the game grid.

### 4. `TERenderer.java` and `TETile.java`
- These files are part of the TileEngine package and provide functionality for rendering the game world.

### 5. `Tileset.java`
- Defines tile sets used in the game, such as floor tiles, walls, and avatars.

### 6. `Utils.java`
- Contains utility methods used throughout the program, such as file I/O operations.

## Classes and Data Structures
- The program uses classes such as `Engine`, `WorldGenerator`, and `TERenderer` to manage game logic, world generation, and rendering.
- Data structures like lists, maps, and arrays are used to store game elements, questions, answers, and the game world itself.

## Algorithms
- Procedural generation algorithms are employed in the `WorldGenerator` class to create random game environments, including rooms, hallways, and walls.
- Sorting algorithms like insertion sort, selection sort, heap sort, merge sort, and quicksort are used as part of the game's mechanics.

## Persistence
- The program supports persistence through file I/O operations handled in the `Utils` class.
- Users can save and load game states, allowing them to resume gameplay or replay saved sessions.

## Dependencies
- The project utilizes the `edu.princeton.cs.introcs.StdDraw` library for graphical user interface components.
- Java's built-in libraries are used for random number generation, file handling, and other core functionalities.

## Getting Started
To run the program:
1. Compile all Java files in the `byow` package.
2. Execute the `Main` class with appropriate command-line arguments (`-s` for input string mode, `-p` for future features, default for keyboard mode).

For detailed usage instructions and gameplay mechanics, refer to the program's documentation or comments within the source code.

