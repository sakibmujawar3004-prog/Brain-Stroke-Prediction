# Brain-Stroke-Prediction
Stroke prediction using machine learning techniques with data preprocessing, exploratory data analysis, feature engineering, and classification models.

📊 **Dataset**  
- **Source**: [Kaggle - Stroke Prediction Dataset](https://www.kaggle.com/datasets/zzettrkalpakbal/full-filled-brain-stroke-dataset)
- **Size**: 5110 records, 12 features  
- **Features**:
  - gender (Male, Female, Other)
  - age
  - hypertension (0 = No, 1 = Yes)
  - heart_disease (0 = No, 1 = Yes)
  - ever_married (Yes/No)
  - work_type (Private, Self-employed, Govt job, etc.)
  - Residence_type (Urban/Rural)
  - avg_glucose_level
  - bmi
  - smoking_status (formerly smoked, never smoked, smokes, unknown)
  - stroke (0 = No, 1 = Yes) (Target Variable)


🛠️ **Methodology**

**Data Preprocessing**:
- Handling missing values in BMI (replacing with mean).
- Encoding categorical variables using Label Encoding and One-Hot Encoding.
- Feature Scaling using StandardScaler for numerical features.
- Handling class imbalance using SMOTE (Synthetic Minority Oversampling Technique).


**Model Training & Evaluation**:
- **Baseline Model**: Logistic Regression.
- **Other Models Tested**: Decision Tree, Random Forest, XGBoost.
- **Evaluation Metrics**: Accuracy, Precision, Recall, F1-score, Confusion Matrix.


