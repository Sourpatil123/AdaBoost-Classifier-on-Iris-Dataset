# AdaBoost-Classifier-on-Iris-Dataset

This project demonstrates how to build, train, and evaluate an AdaBoost classification model using the famous Iris flower dataset. The dataset contains measurements of iris flowers (features) and their species labels (target).
The main goal is to classify iris species based on four key flower characteristics.

📌 Features Used

The dataset contains the following numerical features:

| Feature Name     | Description              |
| ---------------- | ------------------------ |
| **sepal_length** | Length of the sepal (cm) |
| **sepal_width**  | Width of the sepal (cm)  |
| **petal_length** | Length of the petal (cm) |
| **petal_width**  | Width of the petal (cm)  |

🎯 Target Variable

| Column      | Description                                             |
| ----------- | ------------------------------------------------------- |
| **species** | The type of Iris flower (Setosa, Versicolor, Virginica) |


🚀 Project Workflow

Data Loading
Load the Iris dataset using pandas or sklearn.

Exploratory Data Analysis (EDA)

Check data shape, missing values

Visualize distributions and correlations

Understand class balance

Data Preprocessing

Split into train and test sets

Encode target labels if necessary

Model Training (AdaBoost)

Use AdaBoostClassifier from sklearn.ensemble

Train using decision trees as base estimators

Model Evaluation

Accuracy score

Result Visualization

Graphs showing feature importance

📊 Model Used: AdaBoost Classifier

AdaBoost (Adaptive Boosting) works by combining multiple weak learners (usually small decision trees) to build a strong final model.

Why AdaBoost?

Great for tabular datasets

Automatically adjusts weights for hard-to-classify samples

Interpretable due to feature importance

Works well even with simple base estimators

🧪 Evaluation Metrics

Accuracy

Precision, Recall, F1-score

Confusion Matrix

Feature Importance

🛠️ Technologies / Libraries

Python 3.x

NumPy

Pandas

Scikit-learn

Matplotlib / Seaborn (optional for visualization)

Confusion matrix

Classification report
