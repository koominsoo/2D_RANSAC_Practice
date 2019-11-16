# Image Stitching (Panorama)  
  
**KR-CN-JP:** 파노라마 - 全景画卷 - パノラマ  
**Keywords:** ORB (Oriented FAST and rotated BRIEF), RANSAC (RANdom SAmple Consensus)
  
2 pipelines were implemented for image stitching, in this case, panorama. They are ORB + RANSAC and ORB + Least Squares. 
For datasets, I used images from University of Adelaide, CS Dept. Demos below are implemented with case22 and case26 from 2nd dataset. ![Dataset Link](https://cs.adelaide.edu.au/~tjchin/apap/files/images2.zip)  

  Fig 1. Case 22 by ORB + RANSAC  
  
  
  Fig 2. Case 22 by ORB + Least Squares  
  
  
  Fig 3. Case 26 by ORB + RANSAC  
  
  
  Fig 4. Case 26 by ORB + Least Squares  
  
  
Citation:  
[\[1\] Zaragoza, Julio, et al. "As-projective-as-possible image stitching with moving DLT." Proceedings of the IEEE conference on computer vision and pattern recognition. 2013.](https://cs.adelaide.edu.au/~tjchin/apap/)  
[\[2\] Bethel, J. "Least squares image matching for CE604." Purdue University (1997).](https://engineering.purdue.edu/~bethel/main1.pdf)  
[\[3\] Rublee, Ethan, et al. "ORB: An efficient alternative to SIFT or SURF." ICCV. Vol. 11. No. 1. 2011.](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.370.4395&rep=rep1&type=pdf)  
[\[4\] Fischler, Martin A., and Robert C. Bolles. "Random sample consensus: a paradigm for model fitting with applications to image analysis and automated cartography." Communications of the ACM 24.6 (1981): 381-395.](https://dl.acm.org/citation.cfm?id=358692)

Assistive Materials:  
[\[1\] Bethmann, Folkmar, and Thomas Luhmann. "Least-squares matching with advanced geometric transformation models." Photogrammetrie-Fernerkundung-Geoinformation 2011.2 (2011): 57-69.](https://www.isprs.org/proceedings/xxxvIII/part5/papers/89.pdf)
