# ⚕️ Diabetes Prediction using Machine Learning
This project usses patient data to build machine learning models that predict whether an individual has diabetes. Early prediction can help improve health outcomes and potentially save lives.
___________________________________________________________________________________________________

📁 **Dataset**
- **Name:** Pima Indians Diabetes Dataset
- **Source:** https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database
- **Rows:** 768
- **Features:** 8 medical predictors (e.g., Glucose, BMI, Blood Pressure)
- **Target:** *Outcome* - 1 = Diabetes, 0 = No Diabetes

___________________________________________________________________________________________________

🧼 **Data Preprocessing**
- Replaced zero values in critical medical columns with **median values.**
- Normalized features (for logistic regression) using *StandardScaler*.

_________________________________________________________________________________________________

| Model                 | Accuracy | F1-Score (Diabetes) |
| --------------------- | -------- | ------------------- |
| Logistic Regression   | 75%      | 0.64                |
| Decision Tree         | 72%      | 0.62                |
| Random Forest (Tuned) | 75%      | 0.67                |

🟢**Random Forest with hyperparameter tuning performed best in detecting diabetes cases.**
_________________________________________________________________________________________________

📈 **Visualizations**
- Confusion Matrices
- Feature Importance from Random Forest
- Bar Charts comparing Accuracy and F1-Score of all models

_________________________________________________________________________________________________

✔️ **Conclusion**
This project demonstrates how AI can be applied in healthcare to assist in early diagnisis of diabetes. It compares multiple models and highlights the importance of data cleaning, feature importance, and evaluation metrics beyond accuracy (like F1-score).

_________________________________________________________________________________________________
💡**Future Improvements**
- Try other models like XGBoost or SVM
- Explore more feature engineering
- Apply cross-validation and ensembling

_________________________________________________________________________________________________
👤 **Author**
**Dickson Houmbie**
🔬 Focus: AI for Healthcare | Machine Learning for Early Disease Detection

_________________________________________________________________________________________________

## License

This project is protected under copyright law.  
All rights reserved © 2025 Dickson Houmbie. Unauthorized use is prohibited.

For permission requests, contact: hdickson.prof@gmail.com




