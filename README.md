# Detecting-Lanes-Advanced
The following project detects lane lines on a highway, using advanced concepts of Computer Vision.

## Table of Content

1. Camera-Calibration-Chessboard.ipynb
 - Contains the code which reads a series of chessboard images and calculates the distortion co-efficient and calibration matrix for the camera.
 - These parameters are stored in camera_calibration.p pickle file.
 
 2. Finding-Lanes.ipynb
  - The python noteboook consists of the pipeline used to detect lane lines in the test images and videos.
 
 3. camera-cal
  - Calibration images
  
 4. camera_calibration.p
  - pickle file consisting of calibration parameters

## Requirements

- OpenCV
- Python

## Usage

- Use Camera-Calibration-Chessboard.ipynb to calcualte the calibration parameters. Use the images provided in the camera_cal folder to calibrate
- Now, use Finding-Lanes.ipynb file to detect lanes in images and videos. [Do change the code lines to specify the path of your test images and videos]

## Issues

- One of the issues in this approach is that the region of interest i.e. the region where the probability of finding the lanes is maximum is selected manually which does not adhere with the concept of intelligence systems. After all humans are never given region of interest to find lanes, they classify the entire scene into various components.
- Similar approach needs to be followed for detecting lanes.

## License

Provided in the repo
