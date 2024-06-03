Navigation with IMU and Magnetometer

Overview
This repository contains the code and data analysis for the project "Navigation with IMU and Magnetometer." The project aims to estimate heading and velocity using data from an IMU and a magnetometer, and to perform dead reckoning for navigation.

Camera Calibration
Camera calibration is essential for correcting lens distortion and determining camera parameters. The calibration process involved capturing images of a 7x9 checkerboard and using the Caltech Camera Calibration Toolbox. The accuracy of the calibration was assessed by manually identifying the checkerboard corners in each image.

Image Mosaicing
Latino Student Center (LSC) Mural
Images of the LSC mural were captured and stitched together to create a panoramic view. The Harris Corner detection was used to identify feature points, and the final mosaic was adjusted for optimal feature point inclusion.

Cinder Wall
Images of a cinder wall were stitched together using Harris Corner detection with 1000 feature points. The resulting mosaic showed good alignment and feature detection.

Graffiti
Images of graffiti with approximately 50% overlap were stitched together using Harris Corner detection with 1200 feature points. The final panoramic image showed minor misalignments, likely due to human error during image capture.

Mural at Ruggles
Images of a mural at Ruggles with approximately 15% overlap were stitched together using Harris Corner detection with 1400 feature points. The algorithm performed effectively with less overlap by increasing the number of feature points.

Conclusion
The project successfully estimated heading and velocity using IMU and magnetometer data. Camera calibration and image mosaicing tasks provided valuable insights into sensor performance and the importance of calibration and noise reduction.