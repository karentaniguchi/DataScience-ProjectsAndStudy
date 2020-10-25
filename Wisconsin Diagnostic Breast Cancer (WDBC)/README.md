# Wisconsin Diagnostic Breast Cancer (WDBC)

This repository contains the development of a pattern classifier in the Wisconsin Diagnostic Breast Cancer (WDBC) dataset.


# Dataset

The attributes of this dataset were obtained by analysing an digitalized image obtained in fine needle aspirate (FNA) of a breast mass. These attributes describe the characteristics of the cell nuclei present in the image.

Ten real-valued features are computed for each cell nucleus:

  - radius (mean of distances from center to points on the perimeter)
  - texture (standard deviation of gray-scale values)
  - perimeter
  - area
  - smoothness (local variation in radius lengths)
  - compactness (perimeter^2 / area - 1.0)
  - concavity (severity of concave portions of the contour)
  - concave points (number of concave portions of the contour)
  - symmetry
  - fractal dimension ("coastline approximation" - 1)

Each of the ten listed features above have 3 values i) Mean, ii) Standard Error and iii) Worst.

The diagostic feature presents 2 classes (M = malignant, B = benign).

# Dataset Authors

1. Dr. William H. Wolberg, General Surgery Dept.
University of Wisconsin, Clinical Sciences Center
Madison, WI 53792
wolberg '@' eagle.surgery.wisc.edu

2. W. Nick Street, Computer Sciences Dept.
University of Wisconsin, 1210 West Dayton St., Madison, WI 53706
street '@' cs.wisc.edu 608-262-6619

3. Olvi L. Mangasarian, Computer Sciences Dept.
University of Wisconsin, 1210 West Dayton St., Madison, WI 53706
olvi '@' cs.wisc.edu