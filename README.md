# Heart Disease Classification Project

Welcome to the Heart Disease Classification project repository! In this machine learning project, the heart disease dataset (`heart.csv`) from Kaggle is utilized for classification. The project involves loading the dataset, removing outliers, converting text columns to numbers using label encoding and one-hot encoding, applying scaling, and building classification models using Support Vector Machine (SVM) and Decision Tree. Both standalone models and Bagging models are implemented to observe any differences in performance.

## Project Overview

### Dataset

- **Heart Disease Dataset:**
  - The dataset contains features related to heart health.
  - Downloaded from [Kaggle - Heart Failure Prediction](https://www.kaggle.com/fedesoriano/heart-failure-prediction).

### Data Preprocessing

- **Outlier Removal:**
  - Outliers are removed using Z score to enhance data quality.

- **Text to Number Conversion:**
  - Text columns are converted to numbers using label encoding and one-hot encoding.

- **Scaling:**
  - Features are scaled to ensure uniformity in the dataset.

### Model Building

- **Support Vector Machine (SVM):**
  - A standalone SVM model is built to predict heart disease.
  - A Bagging model with SVM as the base estimator is also implemented to compare performance.

- **Decision Tree Classifier:**
  - A standalone Decision Tree model is built for heart disease prediction.
  - A Bagging model with Decision Tree as the base estimator is implemented to compare performance.

### Model Comparison and Bagging Analysis

- **Performance Comparison:**
  - The performance of SVM and Decision Tree classifiers is compared.
  - Bagging's impact on model performance is analyzed.

- **Bagging Conditions:**
  - Research is conducted to understand the conditions where Bagging works best.

## Project Execution

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-username/heart-disease-classification.git
   cd heart-disease-classification
   ```

2. **Download Dataset:**
   - Download the heart disease dataset (`heart.csv`) and place it in the `Exercise` folder.

3. **Run the Project:**
   - Execute the Jupyter Notebook (`heart_disease_classification.ipynb`) in your preferred environment.

4. **Follow Notebook Instructions:**
   - Run the notebook cells sequentially to load the data, preprocess it, build classification models, and compare their performance.

## Note

This Heart Disease Classification project explores the application of SVM and Decision Tree classifiers on a heart disease dataset. The use of Bagging is examined to observe any enhancements in model performance. Consider the conditions under which Bagging works best and analyze the trade-offs in different scenarios.

Feel free to explore, modify, and utilize this project for heart disease classification tasks. If you have any questions or suggestions, please create an issue in the repository.

Uncover the secrets of heart health with the Heart Disease Classification project! ❤️📈💻
