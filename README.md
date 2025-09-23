
# Titanic survial prediction 🚢

This project analyzes the Titanic dataset to understand survival factors and applies machine learning models to predict passenger survival.

## 📌 Steps Covered
1.Data Cleaning & Preprocessing  
   - Handling missing values (Age → median, Cabin → dropped, Embarked → mode)  
   - Encoding categorical variables (Sex, Embarked)  

2. Exploratory Data Analysis (EDA)  
   - Distribution plots (Age, Fare, Pclass, etc.)  
   - Count plots for categorical features  
   - Correlation heatmap & insights  

3. Model Building  
   - Logistic Regression  
   - KNN  
   - Decision Tree  
   - Random Forest  

4. Model Evaluation  
   - Train-test split (80:20)  
   - Accuracy scores  
   - Confusion Matrix & Classification Report  
   - Cross-validation  

5. Results  
   - Logistic Regression and Random Forest performed the best  
   - Final accuracy: **~82% (cross-validation mean)**  

## 📊 Key Insights
- Females had much higher survival rates compared to males.  
- Higher-class passengers (Pclass 1) survived more often than lower classes.  
- Age and fare also influenced survival chances.  

## ✅ Conclusion
The project demonstrates how EDA combined with classification models can provide meaningful insights into survival prediction. Logistic Regression and Random Forest provided stable baseline models. Future work could include feature engineering and advanced ensemble methods.  

---
# Thank you
