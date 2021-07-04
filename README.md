# Image-Cartoonizer
## The Goal
Nowadays Instagram and Snapchat filters of cartoons are quite common. So try to make an image cartoonizer that transforms images into its cartoon using classical computer vision techniques of image processing.
## The Algorithm
### Detecting and boldening edges- 
First the image is converted to a grayscale image and then median blur has been applied to it so that number of undesired edges can be reduced. After this adaptive
threholding has been applied to convert our grayscale image into the binary image to emphasize black edges around the object in the image.
### Image Filtering- 
Bilateral Filter has been used to smoothen flat regions of the image and sharpen the edges
### Color Quantization- 
This method uses a K-means clustering algorithm to reduce the number of colors in our image thus helping us in making our image look more cartoonish.
### Combining - 
The edges and the blurred quantized and processed image will now be combined to get us the final cartoon image
### References-
https://stacks.stanford.edu/file/druid:yt916dh6570/Dade_Toonify.pdf
https://docs.opencv.org/3.4/d6/d00/tutorial_py_root.html
