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

# Installation
```
pip install opencv-python
```

## Credits 

1) Guassian Blur : https://docs.opencv.org/3.1.0/d4/d13/tutorial_py_filtering.html
2) SO article on guassian Blur https://computergraphics.stackexchange.com/questions/39/how-is-gaussian-blur-implemented
3) Vipul Sharma Github : https://github.com/vipul-sharma20/document-scanner
4) Canny Edge Deetction  https://opencv-python-tutroals.readthedocs.io/en/latest/py_tutorials/py_imgproc/py_canny/py_canny.html
5)Contours Documentation :  https://docs.opencv.org/3.1.0/d4/d73/tutorial_py_contours_begin.html
6) ArcLength Documentation:  https://docs.opencv.org/3.1.0/dd/d49/tutorial_py_contour_features.html
7) Perspective Transform Pyimage Search Tutorial https://www.pyimagesearch.com/2014/08/25/4-point-opencv-getperspective-transform-example/
