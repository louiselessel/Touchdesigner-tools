# Convert shaders
Converts shadertoy shaders to touchdesigner format and to raspberry pi format
- From Shadertoy to Touchdesigner
- From Shadertoy to Touchdesigner to Raspberry Pi 4 (using the pi3D library)

Quickly copy paste any code from shadertoy into your project.
The tox is set up with mouse input and all of the other variables already.
Also work for shaders with video input. No audio input yet.
No API key needed.

## How to use:
Simply paste the code into one of the operators called "paste_shadertoy_here". Make sure to connect it to the op called "SHADERTOY_to_TD".
Then click the "Make TD Shader" button. 

Now the shader should run in touchdesigner.
If there are issues with the automatic conversion, they'll show in the glsl1_info1 operator like usual. Then you can fix the line that causes the issue.

You can also convert the shader to run on a Raspberry Pi 4, and up to 4k screens from it. 
Or Hub75 LED matrixes.
Click the "Make Pi Shader" button.
Now you can grab the code and run it using the library linked below. 
If the shader runs in touchdesigner, it'll run on the pi as well.

## Issues?
If you have any issues read the operators labeled HOW TO and check the Textport before submitting an issue on Github.
The goal is for all shaders to convert automatically, so if one doesn't let me know.

Make sure your program [ O|I ] button is set to ON and is playing (not paused).
Some shadertoy shaders require an input, so make sure you plug in a video if one is required for the shader to run. There is already one plugged in. 


## For running shaders on Raspberry pi4:
Download this repo: https://github.com/louiselessel/Shaders-on-raspberry-pi4
Then paste generated shader code from the op called "Pi4 shadercode" into the file called "nameofshader.fs". Follow additional directions described in the repo to get it running on the pi.

## PLEASE NOTE
YOU CANNOT USE A SHADER COMMERCIALLY WITHOUT PERMISSION FROM THE AUTHOR
If you wish to use a Shadertoy shader in a commercial environment, you must contact the original author of the shader and obtain permission. Usually the author will also include the license information as a comment in the shader's code.

For the 3 shaders included, there is a link to the original.


## Other options:
See also this project by Mathew Watchter that allows you to use the Shadertoy API to view and browse shaders https://github.com/matthewwachter/td-shadertoy
