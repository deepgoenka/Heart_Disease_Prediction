# Heart Disease Prediction

This repository contains a machine learning project that predicts the presence of heart disease based on various medical features.

### Libraries Used

- Pandas: For data manipulation and analysis.
- NumPy: For numerical computations.
- Scikit-learn: For machine learning algorithms and model evaluation.
- Matplotlib and Seaborn: For data visualization.
- Pickle: For saving and loading trained models.
- Warnings: For handling warning messages during execution.

### Data Preprocessing

- Imported the dataset and explored its structure and summary statistics.
- Visualized the distribution of labels (No Heart Disease vs. Heart Disease) using a countplot.
- Checked for missing values in the dataset.

### Model Training and Evaluation

Three machine learning algorithms were employed for classification:

1. **Logistic Regression**: Achieved an accuracy of 84.88%.
2. **Support Vector Machine (SVM)**: Also achieved an accuracy of 85.85%.
3. **Random Forest**: Attained an impressive accuracy of 98.54%.

Each model was trained, evaluated, and its performance visualized using a confusion matrix.

### Model Deployment

The Random Forest model was chosen for deployment due to its high accuracy. It was saved as `Heart_Disease_Model.sav` using Pickle.
