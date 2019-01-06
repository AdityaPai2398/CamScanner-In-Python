# CamScanner-In-Python
Build your own document scanner with OpenCV Python

Video DEMO and TUTORIAL : https://www.youtube.com/watch?v=PV0uxIfy_-A

## What is this ?
The script takes an image as input and then scans the document from the image by applying few image processing techniques and gives the output image with scanned effect

## How does it do this?
Initially we need to resize the images so OpenCV can handle it and then the following functions are applied
1) Guassian Blur to smoothen image.
2) Canny Edges to detect the edges.
3) Find contours and boundary of the page
4) Map the end points of contours to 800 * 800 window
5) Apply perspective trasform to get scanned or bird eye view of the image.

## This is shit, why did you build this?
I was BORED :/ 

# INSTALLATION 
```
pip install opencv-python
```
