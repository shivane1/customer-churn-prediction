# 📉 Customer Churn Prediction

This project aims to build a robust machine learning model to predict customer churn based on historical behavioral and transactional data. The goal is to help businesses proactively identify at-risk customers and take action to retain them.

## 🚀 Features
- Data preprocessing and feature engineering
- Handling missing values using Iterative Imputer with Random Forest
- Balancing classes using SMOTE (Synthetic Minority Oversampling Technique)
- Model training and comparison across multiple algorithms
- Final deployment using XGBoost for best performance
- Feature importance analysis to identify key churn drivers

## 🧠 Algorithms Used
- Logistic Regression
- Random Forest Classifier
- XGBoost Classifier ✅ *(Best Performer: 99.3% Accuracy, 97.9% F1-Score)*
- K-Nearest Neighbors
- Gradient Boosting
- AdaBoost, BaggingClassifier, RidgeClassifier

## 🧰 Tech Stack
- Python
- Scikit-learn
- XGBoost
- imbalanced-learn (SMOTE)
- Pandas, NumPy
- Matplotlib, Seaborn (for EDA & visualizations)

## 📊 Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- Cross-validation

## 📈 Results
| Model                  | Accuracy | Precision | Recall | F1-Score |
|------------------------|----------|-----------|--------|----------|
| **XGBoostClassifier**  | 99.3%    | 98.2%     | 97.6%  | 97.9%    |
| RandomForestClassifier | 98.6%    | 98.9%     | 92.5%  | 95.6%    |
| BaggingClassifier      | 98.0%    | 96.9%     | 90.9%  | 93.8%    |

## 📁 Folder Structure





## 📌 Key Takeaways
- SMOTE significantly improved minority class recall
- XGBoost outperformed all other models in both precision and F1-score
- Feature importance revealed critical churn indicators (e.g., support requests, order frequency)

## 💡 Future Work
- Integrate with a live dashboard for real-time churn monitoring
- Deploy as an API or web app for business use
- Include NLP features (e.g., from support tickets) for richer prediction

## 🧑‍💻 Author
Shivane Kapoor  
[GitHub](https://github.com/shivane1) | [LinkedIn](https://linkedin.com/in/shivane)

---




link:- https://clinquant-rabanadas-1d3223.netlify.app/
