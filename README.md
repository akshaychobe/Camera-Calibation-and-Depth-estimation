# Camera-Calibration-and-Depth-Estimation
=====================================================

## Project Overview
--------------------

This project implements a camera calibration and depth estimation algorithm using OpenCV. The algorithm uses a checkerboard pattern to estimate the intrinsic camera matrix and distortion coefficients, and then uses the geometry of similar triangles to estimate the depth of objects in the scene.

## Getting Started
-------------------

### Prerequisites

* Python 3.7 or later
* OpenCV 4.5 or later
* NumPy 1.20 or later

### Running the Code

1. The script will perform camera calibration, undistortion, depth estimation, and verification using the provided dataset.

## Code Structure
-------------------

### Files

* `code.py`: Contains Python code for camera calibration, undistortion, depth estimation, and verification
* `CV_Task__2.pdf`: Report pdf for this task.

### Functions

* `main.py`: Python script that executes the camera calibration, undistortion, depth estimation, and verification algorithm
* `camera_calibration.py`: Python function that performs camera calibration using OpenCV
* `undistortion.py`: Python function that undistorts images using the distortion coefficients and camera matrix
* `depth_estimation.py`: Python function that estimates depth using the intrinsic camera matrix and geometry of similar triangles
* `verification.py`: Python function that verifies the accuracy of depth estimation
* `intrinsic_matrix.py`: Function that Estimated intrinsic camera matrix
* `distortion_coefficients.py`: Function that Estimated distortion coefficients


## Results
------------

The project produces the following results:

* Estimated intrinsic camera matrix and distortion coefficients
* Undistorted images
* Estimated depth values for objects in the scene
* Error analysis and comparison with ground truth values
