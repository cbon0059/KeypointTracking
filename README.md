# KeypointTracking
Implemented Harris Corner detection + Horn and Schunck optical flow to track keypoints 

## Harris Corner Detection
1. Calculate Image gradients I<sub>x</sub>, I<sub>y</sub> (using Sobel Filter)
1. Calculated second order derivatives 
    1. I<sub>xx</sub>
    1. I<sub>yy</sub>
    1. I<sub>yx</sub>
1. For every pixel intensity calculate:
    1. Covariance matrix
    1. Eigenvalues
    1. R-value
1. Calculate local-maxima peaks 

## Horn & Schunck Optical Flow

