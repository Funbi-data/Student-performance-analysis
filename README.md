# 🎓 Student Performance Prediction Using Machine Learning

## 📌 Project Overview
This project analyzes the key factors influencing student academic performance and builds machine learning models to predict final grades (G3).

The study compares two predictive approaches:
- **Model A:** Includes prior academic performance (G1, G2)
- **Model B:** Excludes prior grades to evaluate behavioral and environmental factors

---

## 🎯 Objectives
- Predict student final grades using machine learning
- Evaluate the impact of behavioral and lifestyle factors
- Compare model performance with and without prior academic data
- Identify key drivers of student success

---

## 📊 Dataset Description
The dataset contains student-related features such as:
- Demographics (age, family background)
- Academic behavior (study time, failures)
- Lifestyle factors (social activities, alcohol consumption)
- Attendance (absences)
- Academic scores (G1, G2, G3)

---

## 🧹 Data Preprocessing
- Checked for missing values (none found)
- Encoded categorical variables using One-Hot Encoding
- Converted boolean values to numerical format
- Split data into training and testing sets

---

## 🤖 Models Used
- Random Forest Regressor

---

## 🔵 Model B: Without Prior Academic Performance
This model predicts student performance using only behavioral and environmental features.

**Results:**
- MAE: 3.14  
- R²: 0.24  

📌 Interpretation:  
Behavioral and environmental factors alone have limited predictive power.

---

## 🟢 Model A: With Prior Academic Performance
This model includes previous grades (G1, G2) as predictors.

**Results:**
- MAE: 1.19  
- R²: 0.79  

📌 Interpretation:  
Including prior academic performance significantly improves prediction accuracy.

---

## 📈 Feature Importance (Top Drivers)
- G2 (Second Period Grade) — dominant predictor
- Absences — strong behavioral factor
- Study-related and demographic variables — minor influence

---

## 🧠 Key Insights
- Prior academic performance is the strongest predictor of final grades
- Attendance plays a critical role in student success
- Behavioral and lifestyle factors have limited standalone impact
- Academic outcomes are partially predictable but influenced by multiple factors

---

## 🏁 Conclusion
This analysis demonstrates that while behavioral and environmental factors contribute to student performance, historical academic results (G1, G2) are the most reliable indicators of future outcomes.

---

## 🛠️ Tools & Technologies
- Python
- Pandas
- NumPy
- Scikit-learn
- Jupyter Notebook / Google Colab

---

## 📂 Project Structure
