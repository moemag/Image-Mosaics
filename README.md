# Image-Mosaics

We implement an image stitcher that uses image warping and homographies to automatically create an image mosaic. We focus on the case where we have two input images that should form the mosaic, where we warp one image into the plane of the second image and display the combined views. This problem gives some practice manipulating homogeneous coordinates, computing homography matrices, and performing image warps.
For simplicity, we specify corresponding pairs of points manually using mouse clicks
