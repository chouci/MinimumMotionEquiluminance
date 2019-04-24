Using the code
Main matlab code for creating equiluminant lights using the minimum-motion procedure. 

Input the number of equiluminant colors you want, and a gray (to make the colors equiluminant to that gray). Each participant will run 60 trials to achieve an equiluminant light. All standard precautions need to be set in place (
This code will create a palatte of any number of equiluminant colors. 

Data is stored in data.mat
The main file to run the experiment is called run.m
Usage: DATA = runequilum_exp(
There are a number of things a you could do.

1. Modify the mubber of steps. Right now there are 400 steps (on each of the n color structures, that are maximally saturated and will cross the equiluminant plane/surface 2 times, opposite each other).

2. Modify the number of equiluminant colors one will be able to extract from the procedure. This amounts to modifying the number of color structures the subject will explore. As stated, each color strucure produces 2 colors equiluminant to a given gray. Given by the userf

3. Give credit if you use the code:
Code was originally created by Charlie Chubb, with a lot of edits and new functions from Ted Wright. Peng Sun, Christian Herrera, and many others from the Chubb-Wrigth Lab and HIP Lab also tweaked heavily the original code for their own experiments. 

If you find this code useful, or you use it in your experiments, please use the following citation, where the procedure is explained in full:

Herrera, Sun, Chubb, Wright, Sperling, 2019 Minimum-Motion Luminance, Some Journal. 





