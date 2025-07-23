# Fall-Prediction-among-elderly

# 🩺 Fall Prediction in Elderly using Machine Learning  

This repository contains a machine learning-based solution to predict fall risk among elderly individuals using the Longitudinal Aging Study in India (LASI) dataset. The goal is to identify high-risk individuals early and enable timely preventive interventions.

---

## 📊 Project Overview  

Falls are a leading cause of injury, disability, and death among older adults worldwide. In India, with its rapidly aging population, timely fall risk detection is crucial to reduce healthcare burdens and improve quality of life.

This project uses health, demographic, and psychosocial variables from the LASI Wave-1 dataset and applies supervised machine learning techniques to predict the probability of falls.

---

## 📦 Dataset  

- **Source:** Longitudinal Aging Study in India (LASI) Wave-1  
- **Size:** ~72,000 respondents aged 45+ from all Indian states and UTs  
- **Key Variables Used:**
  - `ht103`: Fall in last 2 years  
  - Demographics: `age`, `gender`, `residence`  
  - Health variables: `depression_score`, `sleep_trouble`, `multimorbidity`  

---

## 🛠️ Technologies & Libraries  

- **Python 3.x**
- Pandas
- NumPy
- Scikit-learn
- Imbalanced-learn
- Matplotlib, Seaborn
- Pyreadstat (for .dta file reading)

---

## ⚙️ Methodology  

1. **Data Cleaning & Preprocessing**
   - Missing value handling
   - Label Encoding for categorical variables
   - Oversampling using `RandomOverSampler` to address class imbalance  

2. **Modeling**
   - Random Forest Classifier  
   - Hyperparameter tuning via GridSearchCV (5-fold CV using F1-score)  

3. **Evaluation**
   - Accuracy, Precision, Recall, F1-score
   - Confusion Matrix  
   - Feature Importance Analysis  

---

## 📈 Results  

- Achieved balanced prediction performance after handling class imbalance.
- Identified key predictors: **age**, **depression symptoms**, **sleep trouble**, **multimorbidity**
- Potential for targeted clinical interventions and public health fall-prevention policies.

---

## 📌 Future Improvements  

- Integrate additional variables: medication history, physical activity levels.
- Test with other models: XGBoost, LightGBM.
- Deploy as a web-based fall risk screening tool.
- Validate with LASI Wave-2 or other aging datasets.

---

## 📚 References  

- Longitudinal Aging Study in India (LASI) User Guide  
- s12877-025-05813-z.pdf: Clinical context of fall risks  
- Scikit-learn, Imbalanced-learn Documentation  

---

## 🙌 Acknowledgements  

- IIPS Mumbai & LASI Research Team  
- Open-source Python ML community  
- Inspiration from global fall prediction studies  

---

## 📜 License  

This project is released under the MIT License.

---

## 💻 Author  

**RJ (Rahul Kumar)** — NIT India  
*Data Science Enthusiast | AI for Healthcare*

---

## 🌟 If you find this helpful, give it a ⭐ and fork the repo!
