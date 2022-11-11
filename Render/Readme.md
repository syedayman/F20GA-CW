# Modelling process for each object 
### Arcade machine and stool
First i created a wireframe using edges to make the shape of an arcade from the side and then filled it in and extruded the edge loop to make the body, 
then i added insets and depth to give it more structure. Then i made the joystick and buttons using cylinder and UV sphere meshe and joined them to the machine. 
For the materials i used image textures from google images as the decal on the side of the arcade machine and its color using the dropper for the rest of the body 
and for the arcade screen i used another image texture of the gameplay screen and added emmision shaders to make it appear like a real screen.
For the stools i used a cylinder mesh and subdivision modifiers to create a smooth seat and added cylinders meshes for the legs and added mirror modifier to create
4 legs. Then i added a torus mesh around the seat as rings to make it appear more authentic.

### Vending machine 
I used a mesh cube and scaled to shape. then added subdivisons to create the dispensor, the keypad and the bill and coin acceptors. Materials from google images used 
to make the side and front decal. I had to UV unwrap the front face as it was a curved surface and fit to shape under UV editing tab.

### Pool table and pool balls
I used a cube mesh and cut in half and applied the mirror modifier to reduce editing time and provide proper symmetry. I added lots of subdivisions to the top face 
so i could select a few faces and apply circular loop cuts from the loop tools to create circular table holes. I added a bevel modifier and scaled the 
bottom face down to give it shape and added legs.
For the pool balls i used UV spheres and subdivision surface modifier to smoothen out and then added pool ball image textures and reduce roughness to give the shiny look 
and rotated randomly and placed on top of the pool table to look realistic.

### TV, stand and bean bags
I used a cube mesh and extruded faces accordingly to give shape amd added image texture and emission shader to make the screen appear bright. 
The table is a cube mesh with a mirror modifier and simulated wooden texture to make it look life like. 
Bean bags are UV spheres with cloth simulation and a collison simulation was added to the plane so then when it dropped it made the genuine shape. The material is 
increased in roughness to give a cloth like texture.

### Others
neon lights are faces made by loop cuts in the wall with a color and emission shader added to it with high intensity.
The floor has a built in checekered texture applied to it to fit the vibe of the gaming room.


