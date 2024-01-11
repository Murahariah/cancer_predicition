# cancer_predicition


Here's a descriptive GitHub repository description, incorporating key elements and best practices:

# Cancer Prediction Model for Breast Cancer Diagnosis

This repository contains a machine learning model trained to predict whether a breast cancer tumor is malignant or benign, based on cell nucleus features.

Key features:

Trained model: Includes a saved Logistic Regression model with 97.3% accuracy on the test set.
User input: Interactive Python script for making predictions with user-provided cell nucleus data.
Clear code: Well-structured and commented Python code for model training, saving, loading, and prediction.
Readme instructions: Comprehensive instructions for using the model and code.

Dataset Information:

Target Variable (y):

Diagnosis (M = malignant, B = benign)
Ten features (X) are computed for each cell nucleus:

1. radius (mean of distances from center to points on the perimeter)
2. texture (standard deviation of gray-scale values)
3. perimeter
4. area
5. smoothness (local variation in radius lengths)
6. compactness (perimeter^2 / area - 1.0)
7. concavity (severity of concave portions of the contour)
8. concave points (number of concave portions of the contour)
9. symmetry
 10. fractal dimension (coastline approximation - 1)

For each characteristic three measures are given:

  a. Mean

  b. Standard error

  c. Largest/ Worst


  
