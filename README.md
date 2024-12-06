# ML_CLASSIFICATION
Logistic Regression on the Iris dataset with detailed performance metrics

This project demonstrates the use of Logistic Regression to classify the Iris dataset into its three classes: `setosa`, `versicolor`, and `virginica`. The project includes data preprocessing, model training, evaluation, and visualization of performance metrics.

Overview

The Iris dataset contains 150 samples with 4 features (sepal length, sepal width, petal length, and petal width). The target variable represents three classes of iris flowers:
-Setosa
- Versicolor
- Virginica

This project uses Logistic Regression to classify the data and evaluates its performance using various metrics.

Features

- Model Training: Logistic Regression classifier.
- Metrics: Precision, Recall, Specificity, F1-Score, and Accuracy for each class.
- Visualization: Confusion matrix heatmap to analyze model predictions.

Results

- Accuracy: The accuracy of the model on the test set is displayed.
- Confusion Matrix: A matrix visualizing the correct and incorrect predictions.
- Class-wise Metrics:
  - Precision, Recall, and Specificity for each class.
  - Macro-average Precision, Recall, and F1-Score for overall performance.

Visualization

The confusion matrix heatmap highlights:
- Rows: Actual classes.
- Columns: Predicted classes.
- Diagonal: Correct predictions.
- Off-diagonal: Misclassifications.

Prerequisites

Make sure you have the following Python libraries installed:
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`

Install the dependencies using pip:
```bash
pip install numpy matplotlib seaborn scikit-learn


