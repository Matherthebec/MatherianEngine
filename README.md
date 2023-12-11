# Matherian Engine (VER 1.0)

This is a First Assignment job I developed for Barcelona's UPC MASTER "ADVANCED PROGRAMMING FOR AAA VIDEO GAMES", consisting of a basic Opengl rendering and Camera Engine.
Please note the final result doesn't meet all the requied points due to my nooby experience in C++. With this in mind, I can guarantee I put all my struggle and that's certainly the best I could give so far :)
The Engine is still not able to receive drag and drop elements and not loading 3d models. However it can correctly load triangles and textures by Shaders.

## Guide

 While Right clicking, “WASD,QE” will make you move around the 3d space.
 
 Holding SHIFT duplicates movement speed
 
 ARROW KEYS ("up", "down", "left", "right") will make rotate the camera.

## Known Issues to fix in the next future

 Open/closing IMGUI Console can generate interferences with OpenGL rendering (you can fix it by simply resizing the window or closing the Console)
 
 Resizing the Main window of the engine will mishape the Render : needs to be fixed asap.

 Sporadic framelag on moving the camera due to the lack of proper Delta Time implementation.
 
 Implementing Geometry to load 3d meshes  
