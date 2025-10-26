# Task 4: Predictive Analytics - Iris Species Classification

This project is a machine learning model built to predict the species of an iris flower based on its sepal and petal measurements.

## Project Goal
The objective is to build a **Decision Tree Classifier**, a supervised learning model, and evaluate its performance on unseen data.

## Project Steps

1.  **Load Data:** The Iris dataset was loaded directly from the `scikit-learn` library.
2.  **EDA (Brief):** A `pairplot` was created, which showed that the three iris species are visually separable.
3.  **Data Preparation:** The data was split into `X` (features: sepal length/width, petal length/width) and `y` (target: species).
4.  **Train-Test Split:** The dataset was split into an 80% training set (for the model to learn) and a 20% testing set (to evaluate performance).
5.  **Model Building:** A `DecisionTreeClassifier` was initialized.
6.  **Training:** The model was trained on the `X_train` and `y_train` data.
7.  **Evaluation:** The trained model was used to make predictions on the hidden `X_test` data. The model's predictions were compared to the true answers (`y_test`).

## Results

The model achieved an accuracy of **100.00%** on the test data.

The classification report and confusion matrix confirm that the model made **zero incorrect predictions** for all three species (setosa, versicolor, and virginica). A visualization of the final decision tree shows the logical rules the model learned to classify the flowers.
