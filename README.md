
# Regression : California Housing Dataset

## **Objective**
The goal of this assignment is to evaluate and compare the performance of various regression algorithms on the California Housing dataset to predict median house prices.

---

## **Dataset**
- **Source:** The California Housing dataset from the `sklearn` library.
- **Description:** Contains features related to housing in California and the corresponding median house values.

---

## **Algorithms Implemented**
The following regression algorithms were applied to the dataset:
1. **Linear Regression**
2. **Decision Tree Regressor**
3. **Random Forest Regressor**
4. **Gradient Boosting Regressor**
5. **Support Vector Regressor (SVR)**

---

## **Steps Performed**
1. **Loading and Preprocessing**
   - Loaded the dataset using `fetch_california_housing` from `sklearn`.
   - Converted the dataset into a Pandas DataFrame.
   - Checked for missing values (none found).
   - Standardized the features using `StandardScaler` to ensure consistent scaling.

2. **Training and Evaluation**
   - Split the dataset into training and testing sets (80% training, 20% testing).
   - Trained each regression model on the training data.
   - Evaluated performance on the testing data using the following metrics:
     - **Mean Squared Error (MSE)**
     - **Mean Absolute Error (MAE)**
     - **R-squared Score (R²)**

3. **Comparison**
   - Compared the models based on their performance metrics.
   - Identified the best-performing and worst-performing algorithms.

---

## **Results**
| Model                       | MSE      | MAE      | R²      |
|-----------------------------|----------|----------|---------|
| Linear Regression           | 0.555892 | 0.533200 | 0.575788 |
| Decision Tree Regressor     | 0.506113 | 0.457649 | 0.613775 |
| Random Forest Regressor     | 0.258953 | 0.330066 | 0.802388 |
| Gradient Boosting Regressor | 0.294080 | 0.371723 | 0.775581 |
| Support Vector Regressor    | 0.355198 | 0.397763 | 0.728941 |

- **Best-Performing Model:** Random Forest Regressor (R² = 0.802388)
- **Worst-Performing Model:** Linear Regression (R² = 0.575788)

---

