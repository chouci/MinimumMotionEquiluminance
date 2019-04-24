Using the code
Main matlab code for creating equiluminant lights using the minimum-motion procedure. 

Input the number of equiluminant colors you want, and a gray (to make the colors equiluminant to that gray). Each participant will run a number of trials to achieve an equiluminant light. We found that a minimum of 60 trials are needed for the staircase to reach the equiluminant plane for most participants, for most colors. All standard precautions need to be set in place: the monitor is the only source of light, the monitor is calibrated. Importantly, you need to obtain the spectra of the red, green, blue and gray lights form your monitor. Gray need to be measured at different luminance levels. To do this: create a patch on the screen and measure its spectra using an spectraradiometer. In our experiments, we used the  the patch was created using matlab code to create a patch with RGB values of [255 0 0], [0 255 0], [0 0 255], respectivley, and 125, 150, 175, 200, 225, for the gray levles. Take the measurements in complete darkness, except for the patch on the computer monitor (that is, similar to the experimental conditions).  
This code will create a palatte of any number of equiluminant colors. 

Data is stored in data.mat
The main file to run the experiment is called run.m
Usage: DATA = runequilum_exp(
There are a number of things a you could do.

1. Modify the mubber of steps. Right now there are 400 steps (on each of the n color structures, that are maximally saturated and will cross the equiluminant plane/surface 2 times, opposite each other).

2. Modify the number of equiluminant colors one will be able to extract from the procedure. This amounts to modifying the number of color structures the subject will explore. As stated, each color strucure produces 2 colors equiluminant to a given gray. 

3. Give credit if you use the code:
Code was originally created by Charlie Chubb, with a lot of edits and new functions from Ted Wright. Peng Sun, Christian Herrera, and many others from the Chubb-Wrigth Lab and HIP Lab also tweaked heavily the original code for their own experiments. 




