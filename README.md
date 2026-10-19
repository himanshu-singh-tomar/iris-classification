
# Iris Flower Classification

## 1. Project Overview
This project uses machine learning classification algorithms to predict the species of an iris flower based on its sepal and petal measurements.

## 2. Dataset
The dataset contains measurements of iris flowers and their corresponding species labels.

Features:
- Sepal length
- Sepal width
- Petal length
- Petal width

Target:
- Species

The original dataset contained 150 records. Three exact duplicate rows were removed, leaving 147 records for analysis.

## 3. Libraries Used
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib

## 4. Project Workflow
1. Load and inspect the dataset.
2. Check missing values and duplicate records.
3. Clean duplicate rows.
4. Perform exploratory data analysis.
5. Split the data into training and testing sets.
6. Train Logistic Regression, K-Nearest Neighbors, and Decision Tree classifiers.
7. Compare model performance.
8. Save and verify the selected model.
9. Predict the species of a new flower sample.

## 5. Evaluation
Models were compared using:
- Accuracy
- Precision
- Recall
- F1-score
- Confusion matrices

Refer to the notebook for the actual evaluation results.

## 6. Saved Outputs
- `graphs/`: EDA and model evaluation visualizations.
- `models/best_iris_model.joblib`: Saved best-performing model.
- `notebooks/Iris_Classification.ipynb`: Complete project notebook.

## 7. How to Run
Install the required libraries:

```bash
pip install -r requirements.txt
```

Open `notebooks/Iris_Classification.ipynb` and execute the cells in order.

## 8. Conclusion
The project demonstrates an end-to-end machine learning classification workflow, from data inspection and visualization to model evaluation, saving, and prediction.
