# Predicting Customer Churn & Enhancing Retention Using Machine Learning
Full project report and notebook can be accessed in this repository.

## Project Overview
Customer churn is a critical issue for digital businesses, especially in telecom. This project leverages machine learning to:

- Predict customer churn.
- Analyze the impact of service features on retention.
- Provide data-driven recommendations for customer segmentation and engagement strategies.

## Dataset
Used fictional Telco data (IBM, 2019) consisting of:
- Demographic
- Location
- Population
- Services
- Churn Status

## Key Features
- **Supervised Learning Models**: Logistic Regression, KNN, Random Forest, XGBoost, SVM, Naive Bayes  
- **Unsupervised Learning**: K-Means for customer segmentation  
- **Feature Selection**: Information Gain, Fisher Score  
- **Dimensionality Reduction**: PCA (99% variance retained)  
- **Class Balancing**: SMOTE  
- **Model Evaluation**: Accuracy, Recall, F1-Score (focus on recall due to churn class imbalance)

## Key Findings
- **Logistic Regression** achieved highest recall (93%) and was chosen as the final model.
- **Longer contracts reduce churn** — statistically proven.
- **Service usage alone doesn’t significantly affect churn.**
- Effective use of **feature selection and PCA** improved model performance and training time.

## 🔧 Tools & Tech
- Python (pandas, scikit-learn, matplotlib, seaborn)
- CRISP-DM methodology

## 🚀 Future Enhancements
- Explore deep learning or time-series models.
- Integrate marketing spend data for better retention ROI analysis.
- Use real-time churn feedback to continually improve the model.
