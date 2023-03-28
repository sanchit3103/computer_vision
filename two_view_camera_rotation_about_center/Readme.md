# Two-view Geometry - Camera Rotation about a center

<p align="justify">
This project focuses on detection and matching of features between two images taken by a camera rotated by a certain angle about its center. As the feature matching algorithm includes many noisy features, outlier rejection is also implemented to determine an accurate set of inliers. This is followed by a linear estimation of 2D projective transformation matrix for the camera using the set of inliers. This estimate is further refined through non-linear estimation using the Lavenberg-Marquardt algorithm. The images of the results obtained are shown below.
</p>

## Project implementation

<p align="center">
  
  <img src = "https://user-images.githubusercontent.com/4907348/228251530-3d8e6822-12ca-4656-aaaf-48e2cf634432.png"/>, &nbsp;&nbsp; <img src = "https://user-images.githubusercontent.com/4907348/228252060-6e6f1197-be92-468f-99d1-64c1ec9ec02f.png"/>, &nbsp;&nbsp; <img src = "https://user-images.githubusercontent.com/4907348/228252308-7138efe5-b00d-4911-b75b-e16f6d38df80.png"/>, &nbsp;&nbsp; <img src = "https://user-images.githubusercontent.com/4907348/228252532-2900acd1-5a0d-4a2a-bfe9-65db99d129c8.png" /> 
  
</p>




