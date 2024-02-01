
# Wine Dataset Machine Learning Analysis

## Introduction
This project involves a detailed analysis and classification of wines based on the Wine dataset, which includes 178 samples of three different types of Italian wine categorized by 13 features. The analysis focuses on exploratory data analysis, implementation of the k-Nearest Neighbors (kNN) algorithm, classifier evaluation, and nested cross-validation to understand and predict the wine categories effectively.

## Exploratory Data Analysis (EDA)
- Initial EDA provides insights into the distribution and interaction of selected features within the dataset.
- Noise is introduced to the dataset to simulate real-world conditions and observe the impact on feature distribution and classification accuracy.

## Implementing kNN
- The kNN classifier is implemented and evaluated against the scikit-learn library's implementation to verify the results.

## Classifier Evaluation
- Various metrics such as confusion matrix, accuracy, error rate, precision, recall, and F-beta score are calculated to evaluate the classifier's performance.
- The classifier's performance is tested under both normal and noisy conditions to assess its robustness.

## Summary of Results
- The results are summarized in tables showing the accuracy, chosen k value, and distance metric for both normal and noisy datasets across different folds in a nested cross-validation setup.

## Installation and Usage
To replicate this analysis:
1. Ensure Python is installed along with necessary libraries like scikit-learn, numpy, and matplotlib.
2. Clone the repository and open the `wineDatasetML.ipynb` notebook in Jupyter Notebook or JupyterLab.
3. Execute each cell in the notebook to perform the analysis and view the results.

## Conclusion
The analysis offers valuable insights into the application of machine learning techniques for wine classification. The project demonstrates the effectiveness of kNN and the importance of thorough evaluation metrics in understanding classifier performance under varying conditions.
