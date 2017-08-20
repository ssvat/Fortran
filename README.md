# sdc-alf
## Advanced Lane Finding

In this project, my goal is to write a software pipeline to identify the lane boundaries in a video.

The Project
---

The goals / steps of this project are the following:

* Compute the camera calibration matrix and distortion coefficients given a set of chessboard images.
* Apply a distortion correction to raw images.
* Use color transforms, gradients, etc., to create a thresholded binary image.
* Apply a perspective transform to rectify binary image ("birds-eye view").
* Detect lane pixels and fit to find the lane boundary.
* Determine the curvature of the lane and vehicle position with respect to center.
* Warp the detected lane boundaries back onto the original image.
* Output visual display of the lane boundaries and numerical estimation of lane curvature and vehicle position.

The images for camera calibration are stored in the folder called `camera_cal`.  
The images in `test_images` are for testing my pipeline on single frames.  

This project includes: 
* writeup
* main (Jupyter notebook)
* example output images (image0, image1, image2, image3, image4, image5, image6 png files)
* output video (project_video_output.mp4)

