## Camera Vertex Cull Add-on

This addon helps with just one button to generate a proper camera cull for every vertex, unlike the Blender's implementation which is per-object basis. 

### Features

 - **Camera Cull** - hide a part of the object that is not visible by the camera
 - **Distance Cull** - hide a part of the object which is further than some point

![Example](https://raw.githubusercontent.com/mitkonikov/big-bang-resources/master/blender/CameraVertexCull/Example_01.PNG)

### Installation

1. Download the repository
2. In the Blender Preferences, go to Addons
3. Install the `camera_vertex.cull.py`
4. Enabled it in the preferences

### Usage

 - Select the object you want to be camera culled
 - Go to the Object Properties Panel
 - Under *Camera Vertex Cull*
 - Just enable it!
 - Play with the margin, so it won't cut off parts of your mash

### How it works?

It uses the `Mask` modifier and creates a vertex group which is used to hide the unused vertices.