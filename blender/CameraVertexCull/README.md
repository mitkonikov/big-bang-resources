## Camera Vertex Cull Add-on

This addon helps with just one button to generate a proper camera cull for every vertex, unlike the Blender's implementation which is per-object basis. 

### Installation

Still working on it...

### Usage

 - Select the object you want to be camera culled
 - Go to the Object Properties Panel
 - Under Camera Vertex Cull
 - Just enable it!
 - Play with the margin, so it won't cut off parts of your mash

### How it works?

It uses the `Mask` modifier and creates a vertex group which is used to hide the unused vertices.

### TODO

 - Add Distance Culling
 - Better Comments
 - Split in files