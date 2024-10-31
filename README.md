Heart Disease Prediction using Logistic Regression and Decision Tree

Overview
This project aims to predict heart disease in patients using machine learning algorithms, specifically Logistic Regression and Decision Tree. By analyzing medical data such as age, cholesterol levels, resting ECG, and other features, the models help identify patients at risk of heart disease. The performance of the models is evaluated using metrics such as Accuracy, Precision, Recall, F1-Score, and ROC-AUC.
Dataset
- Source: UCI Heart Disease Dataset or another publicly available heart disease dataset.
- Key Features:
    - Age, Gender, Chest Pain Type, Resting Blood Pressure, Cholesterol, Fasting Blood Sugar, Resting ECG, Max Heart Rate, ST Depression, Exercise Induced Angina, Number of Major Vessels, and Thalassemia.
    - Target: Heart Disease (1 = Disease, 0 = No Disease).

Project Workflow
1. Data Preprocessing:
    - Handle missing values.
    - Normalize/Standardize numerical features.
    - Encode categorical features.
2. Exploratory Data Analysis (EDA):
    - Visualize feature distributions and correlations with heart disease.
    - Examine the relationships between features like age, cholesterol, and heart disease presence.
3. Model Building:
    - Train Logistic Regression and Decision Tree models.
    - Compare the models' performance.
4. Evaluation Metrics:
    - Accuracy: Measures how often the model correctly predicts heart disease.
    - Precision & Recall: Assess the model's ability to identify positive cases correctly.
    - F1-Score: Harmonic mean of precision and recall.
    - ROC-AUC: Measures model performance across different threshold levels.

Technologies Used
- Python
- Scikit-learn (for Logistic Regression and Decision Tree)
- Pandas and NumPy (for data handling)
- Matplotlib and Seaborn (for data visualization)
- Jupyter Notebook (for development)

How to Run
1. Clone the repository:
    git clone https://github.com/yourusername/Heart-disease-prediction-using-logistic-regression-and-decision-tree.git
2. Install dependencies:
    pip install -r requirements.txt
3. Run the Jupyter Notebook or Python script to train the models and view the results.

Results
- Logistic Regression: Achieved an accuracy of ~82% with a balanced precision and recall.
- Decision Tree: Showed strong performance in identifying complex relationships, especially in non-linear data.

Future Enhancements
- Try additional algorithms like Random Forest or Gradient Boosting for improved accuracy.
- Implement cross-validation and hyperparameter tuning for model optimization.
- Deploy the model using Flask or Streamlit for real-time prediction.

Conclusion
This project demonstrates the use of machine learning techniques to assist in the early detection of heart disease, providing valuable insights for healthcare professionals. Both Logistic Regression and Decision Tree offer effective solutions, with trade-offs between interpretability and complexity.

License
This project is licensed under the MIT License. See the LICENSE ([LICENSE](https://github.com/hishaam321/Heart-Prediction-LR-DT/blob/794c2690ca8d71e6ecec13d984e5b70df1fbd467/LICENSE)) file for details.
