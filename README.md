# P1-finding-lane-lines

[![Udacity - Self-Driving Car NanoDegree](https://s3.amazonaws.com/udacity-sdc/github/shield-carnd.svg)](http://www.udacity.com/drive)

This project, is about identifying lane lines on the road. First in an image, and later in a video stream which is a just a series of images. 

The first goal is to write code to identify and draw the lane lines on a few test images. And later copy and paste the code into the block provided to run on a video stream.

Here are images so the most important steps:

the original image:

![](https://github.com/christianreiser/P1-finding-lane-lines/blob/master/P1/output_images/original.jpg)

Grayscale transform

![](https://github.com/christianreiser/P1-finding-lane-lines/blob/master/P1/output_images/gray.jpg)

Canny transform to see the gradient

![](https://github.com/christianreiser/P1-finding-lane-lines/blob/master/P1/output_images/gradient.jpg)

Image mask which only keeps the region of the image defined by the polygon
formed from `vertices`. The rest of the image is set to black.

![](https://github.com/christianreiser/P1-finding-lane-lines/blob/master/P1/output_images/mask.png)

Hough lines drawn on the image

![](https://github.com/christianreiser/P1-finding-lane-lines/blob/master/P1/output_images/combined.png)
