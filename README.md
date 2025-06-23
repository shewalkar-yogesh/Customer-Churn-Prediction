# 📉 Customer Churn Prediction using Machine Learning

This project demonstrates how machine learning can be applied to predict customer churn based on historical user behavior and service usage patterns. It showcases the end-to-end pipeline from data preprocessing to model evaluation, highlighting both technical and business insights.

---

## 🔍 Project Summary

- **Objective:** Predict whether a customer is likely to churn (leave a service) using classification models.
- **Problem Statement:** Customer retention is crucial for service-based businesses. By identifying at-risk customers early, businesses can take proactive steps to retain them.
- **Approach:** Data preprocessing → EDA → Feature Engineering → Model Training → Evaluation → Insights

---

## 🧰 Tools & Technologies Used

- **Language:** Python  
- **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn  
- **Techniques:** Logistic Regression, Random Forest, Model Evaluation Metrics (Accuracy, Precision, Recall, F1-score)  
- **Visualization:** Correlation heatmaps, bar plots, churn distribution analysis  

---

## 📊 Key Highlights

- Performed data cleaning (null handling, encoding, outlier removal)
- Conducted EDA to identify churn patterns and influential features (e.g., contract type, tenure)
- Built classification models using **Logistic Regression** and **Random Forest**
- Achieved up to **85% accuracy** with Random Forest
- Derived actionable insights to reduce churn by targeting high-risk segments

---

## 📈 Model Performance Overview

| Metric        | Logistic Regression | Random Forest |
|---------------|---------------------|---------------|
| Accuracy      | 83%                 | 85%           |
| Precision     | 0.79                | 0.82          |
| Recall        | 0.81                | 0.84          |
| F1-score      | 0.80                | 0.83          |

> ✅ Final Model: **Random Forest** selected for its superior balance across metrics.

---

## 💡 Business Insights

- Customers with month-to-month contracts had significantly higher churn rates.
- Churn was strongly correlated with high service charges and short tenure.
- Targeted retention strategies (e.g., discounts, personalized offers) can be applied to high-risk groups.

---

## 🚀 Future Enhancements

- Add model interpretability with SHAP values
- Deploy model using Streamlit for live predictions
- Automate pipeline using Python scripts or MLflow
- Expand dataset with customer feedback sentiment

---

## 👤 Author

**Yogesh Shewalkar**  
📧 [yogeshshewalkar02@gmail.com](mailto:yogeshshewalkar02@gmail.com)  
🔗 [LinkedIn](https://www.linkedin.com/in/shewalkar-yogesh) | [GitHub](https://github.com/YogeshShewalkar)

---

## 📄 License

This project is for educational and portfolio purposes. Feel free to fork or reference.
