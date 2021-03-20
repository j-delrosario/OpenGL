## OpenGL-Core
WIP lightweight 2D game engine using OpenGL and written in C++, primarily to learn graphics programming.  

Originally forked from https://github.com/TheCherno/OpenGL.git.  

### Included functionality and utilities:  

Main game loop runs two base layers one for the game and one for ImGUI.  
Support for textures, fonts, and spritesheets, texture scaling and rotation.  
Support for batch rendering and custom shaders.  
Includes perspective, orthographic, and an editor camera with full 3D movement.  
Custom random number generator, key and mouse input support.  

Currently adding a global resource manager and better support for animations.  

## OpenGL-Sandbox
Includes boilerplate starter code for a game.

## Usage
Currently only supports Windows.

Using Premake
```
premake5 vs2019
```
`OpenGL-Sandbox.sln` in vs2019.  
`OpenGL-Core/src/` contains the game engine's files.  
`OpenGL-Sandbox/src/` where your application's files go.
