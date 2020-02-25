# Kinect_Depth_Image
< Playing with Microsoft Kinect for Windows and getting depth data >

Introduction

In this project, I would like to learn programming Kinect for Window using pyKynect (Microsotf Kinect SDK v1.8 with python). This device actually not new one but I think it is good start point for learning 3D image processing, and after that we can apply ML algorithms on collected data. I used kinect model 1517 (I found in my lab) which is just compatible with SDK 1.8. It is better if you have kinect Xbox which is worked with SDK 2.0. SDK 2.0 is easier for using and installing. Beside, you can use freenect library instead of Microsoft SDK, an opensouce for Kinect community with more function to handle collected data. But it is little bit difficult to install on window. That lib is good choice for linux and opencv

Setup and Requirements:

 - Kinect for windows 1517
 - Python3.6
 - Microsoft Kinect SDK v1.8
 - Pykinect lib (configured for Python3 - download from: https://github.com/ShrirangaKadam/pykinect-python3.6)
 - opencv
 
Results and Evaluations
 
 - This respos contains 3 main files: Visible camera, Depth camera and elevator control
 - This is basic point for some next project on 3D object detection
 
 References:
 - https://github.com/ShrirangaKadam/pykinect-python3.6
 - https://github.com/Michael0x2a/kinect-guerilla-art/blob/master/PyGameDemo.py#L186
