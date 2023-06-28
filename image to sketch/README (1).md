
# Image to pencil sketch

Import Libraries:

OpenCV is the only library which is needed for the project.

We will also be using matplotlib library for some visualizations which is discussed later.

The following common procedure to achieve a pencil sketch from an RGB color image:

-->Convert the color image to grayscale.

-->Invert the grayscale image to get a negative.

-->Apply a Gaussian blur to the negative from step 2.

-->Blend the grayscale image from step 1 with the blurred negative from step 3 using a color dodge.
