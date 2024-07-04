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

### Installation

1. `git clone https://github.com/your-username/Camera-Calibration-and-Depth-Estimation.git`
2. `pip install -r requirements.txt`

### Running the Code

1. `python main.py`
2. The script will perform camera calibration, undistortion, depth estimation, and verification using the provided dataset.

## Dataset
------------

The project uses the Room with ArUco Markers dataset, which consists of images of a checkerboard pattern with different orientations and distances from the camera. The dataset is stored in the `dataset/` folder.

## Code Structure
-------------------

### Folders

* `code.py`: Contains Python code for camera calibration, undistortion, depth estimation, and verification
* `results/`: Stores the estimated intrinsic camera matrix, distortion coefficients, undistorted images, and depth values

### Files

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
