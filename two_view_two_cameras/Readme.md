# Two-view Geometry - Images from two cameras

<p align="justify">
This project focuses on detection and matching of features between two images taken by two different cameras. As the feature matching algorithm includes many noisy features, outlier rejection is also implemented to determine an accurate set of inliers. This is followed by a linear estimation of fundamental matrix for imaging a 3D scene using the set of inliers. This estimate is further refined through non-linear estimation using the Lavenberg-Marquardt algorithm. The images of the results obtained are shown below.
</p>

## Project implementation

### Feature detection
<p align="center">
  
  <img src = "https://user-images.githubusercontent.com/4907348/228265999-6042cc82-3945-4d9d-be7e-df117bf33a21.png"/>
  
</p>

### Feature matching
<p align="center">
  
  <img src = "https://user-images.githubusercontent.com/4907348/228266200-cafdc493-4f82-465a-92af-ed01323b57c0.png"/>
  
</p>

### Feature matching after outlier rejection
<p align="center">
  
  <img src = "https://user-images.githubusercontent.com/4907348/228266371-894106e5-ce99-4530-88ff-e68d06ba9d00.png"/> 
  
</p>

### Point-to-line mapping using Fundamental matrix estimate
<p align="center">
  
  <img src = "https://user-images.githubusercontent.com/4907348/228266754-0f2e2a66-a561-4ca6-a140-ecf1d4d8524d.png"/> 
  
</p>
