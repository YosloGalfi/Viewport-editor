# Viewport-editor
Viewport editor using Autodesk Maya and Gameplay 3D

Custom viewport editor created with the C++ API for Autodesk Maya and Gameplay 3D. 
The plugin register the various callbacks in the C++ API and sends appropriate information to the gameplay 3D implementation, using a circular buffer. 

The viewport has support for creating and deleting models, editing the models with basic functionalities such as bevel, extrude, smooth e.t.c.. 
You can add, change or remove textures on the models. 
You can group the models in a hierarchy and the viewport will implement the hierarchy, using the final transformation for every model in the dagPath hierarchy. 
You can change the camera in the viewport, as well as zoom in or out and rotate the camera. 
