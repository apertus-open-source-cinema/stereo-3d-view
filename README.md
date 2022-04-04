# stereo-3d-view
OBS plugins for stereo 3d related workflows

# Prerequisites 
Software:
* OBS® Studio (https://obsproject.com/)
* StreamFX (https://github.com/Xaymar/obs-StreamFX)

Hardware: 
To get  live video of two cameras into OBS you require hardware that can capture two video streams.

# Usage

## Anaglyph Mode

The basic idea is to use an additive shader that combines two image/video sources together. For anaglyph mode a corresponding *Color Grading* filter for each source removes either the red or green color channels (for red/green color glasses). A *3D Transform* filter can be used to offset one of the two images if required for convergence adjustments.

![Anaglyph Mode Setup](/documentation/anaglyph01.jpg)
![Anaglyph Mode Setup](/documentation/anaglyph02.jpg)
![Anaglyph Mode Setup](/documentation/anaglyph03.jpg)


## Difference Mode

Here a subtractive shader is used to spot differences between a stereo pair for camera/lens alignment. Again the*3D Transform* filter can be used to offset one of the two images if required for convergence adjustments. No *Color Grading* filter are reqired for Difference Mode.
 
![Anaglyph Mode Setup](/documentation/difference01.jpg)


