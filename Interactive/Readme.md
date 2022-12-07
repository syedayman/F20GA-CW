##Models and materials
The name of the gltf file with the models in the assests folder is called middle.gltf
The models had to be remade in blender as OpenGL could not import the existing models as they were too complex, so I had to remake them in a simpler way and then export only a few models that could be imported by openGL. Another big issue was the fact that openGL can only use one texture per model and i was only able to export one object at a time, thus I had to join all objects together, make the textures very simple and the UV wrap all the textures of all models into one single UV map and then bake the textures. In this way all textures were seen in openGL. I originally could only use image textures when importing single objects as I had to do this with every model first to see which models could work in openGL and which coudn't through trail and error. But later on I was able to use both regaulr textures and materials as well as image textures in openGL. Another issue was the size limitation in openGL which limited the number of objects i could have in my scene. 

##Camera
I also added the camera interaction in the form of steadicam and FPS cam using mouse with the help of the lecture files.

I was unfortunately unable to implement any lighting features
