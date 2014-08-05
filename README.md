Image Stitching
============
1.Introduction
---------------
It's a common project in computer vision course, you can find it in stanford, washington and brown. I borrow skeleton code
from washington cse576.

This project include three main parts:
* detect interest points
* match interst points
* RANSAC refine matches
* stitch two image together

What I did in this project:
* implement sift detector and sift descriptor(this is crazy part, lots detail)
* use SSD matching points
* RANSAC to refine mathes, iterate 500 times
* computer homography then stich two iamge together
* use dynamic programming to find optimum seam, blend along this seam.


Platform: Qt5 vs2013 c++11

2.Result
----------
 Original <br>
![](https://github.com/tpys/seam-carving/raw/master/) <br>
 Vertical Seam Carving <br>
![](https://github.com/tpys/seam-carving/raw/master/) <br>
 Horizontal Seam Carving <br>

3.Issue
--------

