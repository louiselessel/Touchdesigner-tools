# Touchdesigner-tools
Small touchdesigner help tools


## Convert shaders
Converts shaders from different formats to or from touchdesigner format
- From Shadertoy to Touchdesigner
- From Shadertoy to Touchdesigner to Raspberry Pi 4 (using pi3D)

This is a work in progress but it will convert rudamentary shaders with no buffers.

How to use:
Simply paste the code into one of the op called "paste_shadertoy_here".
Make sure to connect it to the op called "SHADERTOY_to_TD".

Click the "Make TD Shader" button.

Click the "Make Pi Shader" button.

Make sure your program [ O|I ] button is set to ON and is playing (not paused).


### For running shaders on pi4: 
Download this repo: https://github.com/louiselessel/Shaders-on-raspberry-pi4

Then paste generated shader code from the op called "Pi4 shadercode" into the file called "nameofshader.fs".
Follow additional directions described in the repo.
