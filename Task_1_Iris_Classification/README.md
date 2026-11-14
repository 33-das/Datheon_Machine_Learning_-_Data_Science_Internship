# Task 1: Multi-Class Classification Using Iris Dataset

## Project Overview

This project implements a multi-class machine learning classification pipeline using the Iris dataset. Two machine learning algorithms, Logistic Regression and Decision Tree Classifier, are trained and evaluated to classify three Iris flower species.

## Objectives

- Load and explore the Iris dataset.
- Perform exploratory data analysis (EDA).
- Normalize numerical features using StandardScaler.
- Split the dataset into training and testing sets (80:20).
- Train Logistic Regression and Decision Tree models.
- Evaluate model performance using classification metrics.
- Visualize confusion matrices and decision boundaries.
- Compare the performance of both classifiers.

## Dataset Information

The Iris dataset contains 150 samples belonging to three species:

- Iris Setosa
- Iris Versicolor
- Iris Virginica

Features:
- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

## Machine Learning Algorithms

1. Logistic Regression
2. Decision Tree Classifier

## Technologies and Libraries

- Python
- Google Colab
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

## Model Performance

| Classifier | Accuracy | Precision | Recall | F1-Score |
|---|---:|---:|---:|---:|
| Logistic Regression | 93.33% | 93.33% | 93.33% | 93.33% |
| Decision Tree | 93.33% | 93.33% | 93.33% | 93.33% |

*Metrics are based on the 20% test split.*

## Visualizations

The project includes:
- Species distribution plot
- Exploratory pair plot
- Logistic Regression confusion matrix
- Decision Tree confusion matrix
- Logistic Regression decision boundary
- Decision Tree decision boundary

The decision boundary visualizations use petal length and petal width, while the main model comparison uses all four features.

## Project Structure

```text
Task_1_Iris_Classification/
├── README.md
├── Notebook/
│   └── Task_1_Iris_Classification.ipynb
└── Results/
    ├── Classifier_Comparison.csv
    ├── Logistic_Regression_Report.csv
    ├── Decision_Tree_Report.csv
    ├── Logistic_Regression_Confusion_Matrix.png
    └── Decision_Tree_Confusion_Matrix.png
```

## Conclusion

Both Logistic Regression and Decision Tree achieved 93.33% accuracy on the test dataset. Their precision, recall, and F1-score were also equal in this experiment.

This project demonstrates the implementation, evaluation, and visualization of a multi-class machine learning classification pipeline.
