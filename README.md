## Diabetes Prediction: Logistic Regression vs. SVM

This Jupyter Notebook (`diabetes_prediction.ipynb`) explores and compares the performance of Logistic Regression and Support Vector Machine (SVM) for predicting diabetes using the Pima Indians Diabetes Dataset. The code performs the following steps:

**1. Data Loading and Preprocessing:**

- Uses MinMaxScaler to normalize feature values between 0 and 1

**2. Model Training and Evaluation:**

- Trains Logistic Regression and SVM models on the preprocessed data
- Splits data into training and testing sets (80/20 split)
- Evaluates the performance of both models using training and testing errors

**3. Comparison and Results:**

- Compares the training and testing errors of Logistic Regression and SVM
- Provides insights into which model performs better for diabetes prediction on this dataset

**Dependencies:**

This notebook requires the following Python libraries:

- pandas
- numpy
- sklearn.linear_model (for Logistic Regression)
- sklearn.svm (for Support Vector Machine)
- sklearn.preprocessing (for MinMaxScaler)
- sklearn.model_selection (for train-test split)

**Running the Notebook:**

1. Ensure you have the required libraries installed.
2. Open the `diabetes_prediction.ipynb` file in a Jupyter Notebook environment.
3. Run the cells sequentially to execute the code and view the results.

**Expected Output:**

The notebook will print the training and testing errors for both Logistic Regression and SVM models. You can then analyze these results to determine which model performs better for predicting diabetes in this specific dataset.

**Additional Notes:**

- This is a basic comparison. You might want to explore hyperparameter tuning for both models to potentially improve their performance.
- Consider using other performance metrics like accuracy, precision, recall, and F1-score for a more comprehensive evaluation. 
