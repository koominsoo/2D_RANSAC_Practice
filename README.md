# Image Stitching (Panorama)  
  
Kr - Cn - Jp: 파노라마 - 全景画卷 - パノラマ  
Keywords: ORB (Oriented FAST and rotated BRIEF), RANSAC (RANdom SAmple Consensus)
  
2 pipelines were implemented for image stitching, in this case, panorama. They are ORB + RANSAC and ORB + Least Squares. 
For datasets, I used images from University of Adelaide, CS Dept.  
Demos below are implemented with case22 and case26 from 2nd dataset.  
![Dataset Link](https://cs.adelaide.edu.au/~tjchin/apap/files/images2.zip)  

Case 22 by method 1  
  
  
Case 22 by method 2  
  
  
Case 26 by method 1  
  
  
Case 26 by method 2  
  
  
Citation:  
![\[1\] Zaragoza, Julio, et al. "As-projective-as-possible image stitching with moving DLT." Proceedings of the IEEE conference on computer vision and pattern recognition. 2013.](https://cs.adelaide.edu.au/~tjchin/apap/)  
![\[2\] Bethel, J. "Least squares image matching for CE604." Purdue University (1997).](https://engineering.purdue.edu/~bethel/main1.pdf)  
![\[3\] Rublee, Ethan, et al. "ORB: An efficient alternative to SIFT or SURF." ICCV. Vol. 11. No. 1. 2011. (http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.370.4395&rep=rep1&type=pdf)  
