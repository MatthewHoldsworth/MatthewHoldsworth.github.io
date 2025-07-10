# My Portfolio 

### Introduction
I’ve had the opportunity to work on a number of incredible projects that I’m pleased to share. Not only do I enjoy showcasing my work, but also sharing details about the creative process behind each project. Feel free to browse through my portfolio.

### Physics Engine C
This is my 4th year project on game engine mechanics such as physics, AI, and automata's. In this project the player can control a goat player object that's object is to collect points and a key to escape a maze, while there is a goose AI that chases the player and points. The game has a time limit of 60 seconds. There are also menus in which the game can be pause and the player can increase or reduce there move speed to change the games difficulty.

Learning Outcomes:
- Experience programming a C++ physics based engine
- Programmed three implementations of AI/state-based behaviours
- Implemented and applied pathfinding algorithms to AI agents

What Could Be Improved:
- Orientation constraints could have been implemented
- Pathfinding could be improved by implementing nav meshes
- More gameplay elements could be added such as better level design/textures
- A proper menu system that appears in game using middleware

[Link to Project](https://github.com/MatthewHoldsworth/PhysicsEngineC)

### Programmatic-Planet-Rendering
This was my dissertation project for 3rd year, the aim of this project was to implement a variety of methods of procedural generation. Then record performance metrics of these methods at many levels of fidelity, and in evaluation compare them against one another.

[Link to Project](https://github.com/MatthewHoldsworth/Programmatic-Planet-Rendering)

### CSC3231-UnityGraphics
This project was an early 3rd year unity project. This was an introduction into game developments aspects such as shaders, scene graphs and particle systems. Its a rough piece of work that I have included as it contains some work I'm proud such as the water shader, camera controls and billboards.

[Link to Project](https://github.com/MatthewHoldsworth/CSC3231-UnityGraphics)

### OpenGLGraphics
4th year C++ project that's focus was on creating a graphics rendering system. This included implementing features such as multiple lights, scene graphs and bump mapping, among others to create a scene that a scene that contains these features while maintaining a high frame rate. This scene also includes shaders that implement greyscale and blending.

Learning Outcomes:
- Used OpenGL to bind and execute shaders in GLSL
- Implemented a scene with multiple light sources
- Used and applied post processing techniques

What Could Be Improved:
- Lighting model could be improved with shadow mapping
- Reflections of mesh geometry could be added to water
- More geometry could be added to main scene along with the animated skeletal mesh

[Link to Project](https://github.com/MatthewHoldsworth/OpenGLGraphics)

### C Programming Module
This project is entirely my own work. This was to solve a problem regarding polynomial equations. The program can generate polynomials according to some specifications in the readme, it can generate a set of outputs for a range of x values. It can save and load output set and regenerate the polynomial equation used to generate them.

[Link to Project](https://github.com/MatthewHoldsworth/CProgrammingModule)

### 3DTBS (3 Dimensional Turn Based Strategy)
This was a hobby project started in January 2024, part of my motivation behind project was to refamiliarise myself with Unity, as well to mimic to gameplay from games I enjoy. The intent was to have a pathfinding system in a grid, like in Fire Emblem or XCOM, where the player could plot the direction and path of the controlled character or if that path was invalid have the game generate the quickest path. The idea being if there was a hazard the player could navigate their character around it or could simply have the game generate the quickest path if number of moves was important. For this I created a grid like map in which each node (tile) is linked to another which represents adjacency. A character with a number of movement points was created and a control scheme implemented to select the character or tiles in the grid. From here a breadth first search algorithm was created, which would get all possible moves of the character and their distance from the characters origin, theses tiles would be highlighted for the user. Then the user hover a tile it is added to a path list, if the tile is invalid due to it already being in the list, the list being greater than the number of moves or the tile being out of range, the game generates its own path of tiles to the destination if possible. When right clicking the character executes its move path, following the tiles within this path.

Contained within this project is some use of Unity features that were new to me such as the Input system, which is used to control the character, an event based system to notify other scripts via components and the UI toolkit, which provides  information about the character selected and the tiles such as names and adjacency.

[Link to Project](https://github.com/MatthewHoldsworth/3DTBS)

[LinkedIn](https://www.linkedin.com/in/matthew-holdsworth-449535264/)

[GitHub](https://github.com/MatthewHoldsworth)
