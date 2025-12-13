/// JavaScript Programming Fundamentals Documentation
In JavaScript programming fundamentals we were tasked with creating and showing off five elements of javascript; the five elements had to display the following:
// Element 1: Demonstration of basic shapes, lighting, textures, shadows, and motion.
// Element 2: Demonstration of a 3D environment placing a selection of individual and cloned textured meshes within a 360-degree scene with background image, textured terrain using a height map, appropriate lighting, and constrained camera motion.
// Element 3: Demonstration of a movable player mesh incorporating player functional animations. Interaction between player and other objects using physics.
// Element 4: Demonstration of a Graphic user interface featuring a menu system and transitions from menu to an interactive scene. At least one GUI element should change in response to scene events.
// Element 5: Demonstration of at least two scenes which can be switched between either by GUI or in response to scene events. Each scene should incorporate the techniques explored in the module.

This documentation is focused on Element 5.

/// Element 5 Documentation

Element 5 features multiple scenes that can be swapped between using buttons implemented through GUI. The fifth element gives the most opportunity to be creative and implement various techniques utilised throughout the course so for my fifth element, I reused previous elements as a foundation for the scenes, modifying the positions and texures of the shapes.

// Scene 1:We have 3 boxes all textured with the reflective mat, 1 sphere textured with grass mat, 1 ground textured with wood mat. 

// Scene 2: we have 1 sphere textured with eye mat, 1 cylinder textured with beans mat, 1 ground textured with grass mat.

// Scene 3: we have 3 spheres textured with reflective mat, earth mat, sun mat , 1 ground textured with dirt mat.

// Scene 4: we have 5 cylinders  textured with reflective mat, 1 ground textured with eye mat.

Prior to being built using "npm run multibuild", the fifth element sat in a folder named "element5", which was made up of two folders: assets and src. The assets folder contains the image that is applied like a texture to the shapes surrounding the sphere in the scenes, and the src folder contained all the typescript files for all the scenes and the GUI.

from there it needed to be pulled to the webpage allowing it to be accessed via commands like buttons to demo the scenes.  

Once built it creates a folder called "dist" which holds the now built files; the index file has changed, pulling from the fresh files within the assets folder.

#Marc Blair#
