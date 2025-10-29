# Breast Cancer Diagnosis Classifier

This project uses a k-nearest neighbors (knn) classifier to diagnose breast cancer patients based on the Breast Cancer Wisconsin (Diagnostic) Database.

## Dataset

The dataset used is the Breast Cancer Wisconsin (Diagnostic) Database, which is included in scikit-learn. It contains 569 instances with 30 numeric, predictive attributes. The features are computed from a digitized image of a fine needle aspirate (FNA) of a breast mass. They describe characteristics of the cell nuclei present in the image.

The target variable is the diagnosis, which is either malignant (encoded as 0) or benign (encoded as 1).

## Model

The model is a k-nearest neighbors (knn) classifier with `n_neighbors = 1`. The data is split into training and test sets, and the model is fit on the training data. The accuracy of the model on the test set is approximately 91.6%.

## How to Run

1.  **Dependencies:** Ensure you have the following Python libraries installed:
    *   numpy
    *   pandas
    *   scikit-learn
    *   matplotlib

2.  **Execution:** You can run the code in a Jupyter Notebook environment by opening and running the `cancer_detector.ipynb` file. Alternatively, you can run the `main.py` script from your terminal:
    ```bash
    python main.py
    ```
    The script will print out the accuracy of the model and display a plot visualizing the prediction scores.
