CamScanner-In-Python

What is this ?
The script takes an image as input and then scans the document from the image by applying few image processing techniques and gives the output image with scanned effect

How does it do this?
Initially we need to resize the images so OpenCV can handle it and then the following functions are applied

Guassian Blur to smoothen image.
Canny Edges to detect the edges.
Find contours and boundary of the page
Map the end points of contours to 800 * 800 window
Apply perspective trasform to get scanned or bird eye view of the image.
