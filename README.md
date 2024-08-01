# Cancer Detection Model

## Project Overview

This project aims to predict cancer presence using various machine learning techniques. The project includes Exploratory Data Analysis (EDA), handling multicollinearity, scaling methods, cross-validation techniques, and model implementation with Support Vector Machine (SVM) using GridSearchCV. The results are evaluated using classification reports.

## Project Structure

- **`Cancer_Prediction.ipynb`**: Jupyter Notebook containing the code for EDA, data processing, model training, cross-validation, and evaluation.
- **`README.md`**: This file providing an overview of the project.

## Steps Involved

1. **Exploratory Data Analysis (EDA)**
   - Understanding the data distribution.
   - Identifying patterns and anomalies.
   - Visualizing data through various plots.

2. **Handling Multicollinearity**
   - Checking for multicollinearity among features.
   - Removing or transforming highly correlated features.

3. **Scaling Methods**
   - **MinMax Scaler**: Scaling features to a fixed range.
   - **Standard Scaler**: Scaling features to have zero mean and unit variance.

4. **Cross-Validation Techniques**
   - **Cross-Validation**: Evaluating model performance by dividing the data into training and validation sets multiple times.
   - **Leave-One-Out Cross-Validation (LOOCV)**: A special case of cross-validation where the number of folds equals the number of data points.
   - **LOOCV with MinMax Scaler**: Applying LOOCV with data scaled using MinMax Scaler.

5. **Model Implementation**
   - **Support Vector Machine (SVM)**: Implementing SVM for classification.
   - **GridSearchCV**: Hyperparameter tuning using GridSearchCV.

6. **Model Evaluation**
   - Viewing results using the classification report, which includes metrics such as precision, recall, f1-score, and accuracy.

## Running the Project

1. **Ensure Required Libraries**: Make sure you have all the necessary libraries installed. You can install them using:
   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn
