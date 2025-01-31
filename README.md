# Spaceship Titanic - Kaggle Competition

This project is my submission for the **Spaceship Titanic** competition on Kaggle. The task is to predict which passengers were transported to an alternate dimension after the Spaceship Titanic collided with a spacetime anomaly. The solution involves building a machine learning model to classify passengers based on available data.

## Problem Overview:
The spaceship, carrying 13,000 passengers, was hit by a spacetime anomaly, causing a portion of the passengers to be transported to an alternate dimension. Your goal is to predict whether a passenger was transported (True) or not (False) based on the provided features in the dataset.

### Evaluation Metric:
The model's performance is evaluated using **classification accuracy**, which is the percentage of correct predictions in the test data. The final accuracy of my model is **0.78746**.

---

## Files in this Repository:

- **train.csv**: The training dataset containing information about passengers (features include age, class, etc.).
- **test.csv**: The test dataset for which predictions need to be made.
- **spaceship.ipynb**: Jupyter notebook containing the data analysis, feature engineering, model training, and evaluation code.
- **submission.csv**: The final predictions on the test dataset in the required submission format.

---

## Approach:

1. **Data Preprocessing**:
   - Loaded and examined the data to identify missing values, outliers, and other inconsistencies.
   - Performed data cleaning (e.g., handling missing values, encoding categorical variables).

2. **Feature Engineering**:
   - Created new features based on available data.
   - Normalized/standardized numerical features where necessary.

3. **Model Building**:
   - Built a classification model using **RandomForestClassifier** (or another suitable algorithm).
   - Used cross-validation for hyperparameter tuning.

4. **Model Evaluation**:
   - Evaluated model performance on the training set and used the **accuracy score** to measure its effectiveness.
   - The final accuracy achieved on the test set is **0.78746**.

5. **Submission**:
   - Predictions for the test dataset were stored in `submission.csv` for Kaggle submission.

---

## Requirements:

- Python 3.x
- Libraries:
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - scikit-learn
  - jupyter (for running the notebook)

---

## How to Run:

1. Clone this repository.
2. Install the required libraries (e.g., via `pip install -r requirements.txt`).
3. Open and run the `spaceship.ipynb` Jupyter notebook for data analysis, model building, and evaluation.
4. The predictions for the test set will be saved in `submission.csv`.

---

## Notes:

- **Accuracy**: The final classification accuracy on the test set is **0.78746**.
- Feel free to explore the notebook for further details on the model building process, hyperparameter tuning, and evaluation.

---
