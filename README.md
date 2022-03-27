# Ball-tracking-by-color

## Objective

To develop a system which will automatically detect and track a particular coloured object and 
follow it

## Methodology

The project I have undertaken can be used as a reference or as a base for realizing a scheme 
to be implemented in other projects of a greater level. I take the data from the camera and use 
the Image Segmentation to classify the color and a specific shape. This keeps a record of the 
object’s center and will see if there is any obstacle in the path and then follows in the path.

The objective was to make a basic prototype for a bot which can sense color and shape of an 
object and follow it. The robot tries to find a color which is hard coded, if it finds a ball of that 
color, it follows it.

For the image analysis, I have taken each frame and then mask it with green. Then I found 
all the contours and found the largest among them and bound it in a circle. The circle is shown on 
the main image and finds the coordinates of the center of the circle. 

## Software Requirements
● Python

● OpenCV
