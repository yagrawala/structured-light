# structured-light
3D reconstruction of a scene, using binary encoded images and reference pixel value handbook as inputs.

Calculate average of the images and use it as reference for lighted and darkened pixels.
Then use the codebook to identify the pixels which are lit up.
Undistort and triangulate points to get 2D points, then use homography to get 3D points from 2D points.

Use CloudCompare to view the .xyz point cloud file.
