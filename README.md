
Chessboard camera calibration

Reference:

    https://medium.com/analytics-vidhya/camera-calibration-with-opencv-f324679c6eb7
    OpenCV-Python Tutorials » Camera Calibration and 3D Reconstruction https://opencv-python-tutroals.readthedocs.io/en/latest/py_tutorials/py_calib3d/py_calibration/py_calibration.html
    https://opencv.org/license/

Calibration using: chessboard

Why chessboard test? A chessboard is great for calibration because it's regular, high contrast pattern makes it easy to detect automatically. And we know how an undistorted flat chessboard looks like. So, we use our camera to take pictures of Chessboard at different angles.
Calibration of:

Single camera
Input:

Set of images of chessboard calibration test from one camera
Output:

    Matrix of intrinsic camera params (mtx)
    Matrix of distortion coefficients (dist)

