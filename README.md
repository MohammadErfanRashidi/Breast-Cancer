# Breast Cancer Prediction using Logistic Regression

This project demonstrates the use of Logistic Regression for predicting breast cancer based on the Wisconsin Breast Cancer Diagnostic dataset.


## Dataset

The dataset used in this project is the Wisconsin Breast Cancer Diagnostic dataset, which contains features computed from a digitized image of a fine needle aspirate (FNA) of a breast mass. These features describe characteristics of the cell nuclei present in the image.

The dataset is available in the file `data.csv`. It includes the following columns:

* **id:** ID number
* **diagnosis:** Diagnosis (M = malignant, B = benign)
* **radius_mean:** Mean of distances from center to points on the perimeter
* **texture_mean:** Standard deviation of gray-scale values
* **perimeter_mean:** Mean size of the core tumor
* **area_mean:** Mean area of the core tumor
* **smoothness_mean:** Mean of local variation in radius lengths
* **compactness_mean:** Mean of perimeter^2 / area - 1.0
* **concavity_mean:** Mean of severity of concave portions of the contour
* **concave points_mean:** Mean for number of concave portions of the contour
* **symmetry_mean:** Mean symmetry
* **fractal_dimension_mean:** Mean "coastline approximation" - 1
* **radius_se:** Standard error for the mean of distances from center to points on the perimeter
* **texture_se:** Standard error for standard deviation of gray-scale values
* **perimeter_se:** Standard error for mean size of the core tumor
* **area_se:** Standard error for mean area of the core tumor
* **smoothness_se:** Standard error for local variation in radius lengths
* **compactness_se:** Standard error for perimeter^2 / area - 1.0
* **concavity_se:** Standard error for severity of concave portions of the contour
* **concave points_se:** Standard error for number of concave portions of the contour
* **symmetry_se:** Standard error for symmetry
* **fractal_dimension_se:** Standard error for "coastline approximation" - 1
* **radius_worst:** "Worst"
