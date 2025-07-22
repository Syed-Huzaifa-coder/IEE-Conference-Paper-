# IEE-Conference-Paper-
# 🧠 Early Prediction of Autism Spectrum Disorder (ASD) using Machine Learning

This repository contains the research and implementation details of our paper titled:  
**"Early Prediction of Autism Spectrum Disorder (ASD) using Machine Learning"**  
This research was conducted as a part of our **Final Year Project - Phase 1** at **Punjab University College of Information Technology (PUCIT)**.

---

## 📄 Overview

Autism Spectrum Disorder (ASD) is a complex neurodevelopmental condition that affects communication, behavior, and social interaction. Early identification is crucial for timely intervention. In this study, we aimed to build an effective machine learning-based framework to predict the risk of ASD using behavioral and developmental data collected from children.

---

## 🎯 Objectives

- Predict ASD at an early stage using questionnaire-based behavioral features.
- Compare multiple machine learning algorithms for performance.
- Identify key predictors contributing most to ASD diagnosis.
- Enable data-driven support for early clinical screening.

---

## 📊 Dataset

- Total Records: **200 children**
  - 100 diagnosed with ASD
  - 100 neurotypical (non-ASD)
- Data Source: Collected through structured questionnaires filled by parents/caregivers via Google Forms and supported by Autism Center Pakistan.
- Features: 15 behavioral and developmental questions (categorical + range-based).

---

## ⚙️ Data Preprocessing

- Label encoding for categorical values (`Yes` → 1, `No` → 0, `Maybe` → intermediate values).
- Missing value imputation using **mode**.
- Feature scaling via **StandardScaler**.
- Feature selection using:
  - Chi-Square Test
  - Random Forest Feature Importance

---

## 🧪 Models Used

We evaluated multiple supervised ML models:

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Decision Tree
- Random Forest
- Support Vector Machine (SVM)
- Naive Bayes
- AdaBoost
- Gradient Boosting
- XGBoost
- Artificial Neural Network (ANN)

---

## 📈 Results

| Model               | Accuracy (%) |
|---------------------|--------------|
| **Random Forest**   | **95**       |
| **XGBoost**         | **95**       |
| **AdaBoost**        | **95**       |
| ANN                 | 95           |
| Logistic Regression | 92.5         |
| SVM                 | 90           |
| KNN                 | 90           |
| Naive Bayes         | 75           |

- **SVM** achieved the highest AUC score: **0.97**
- Most significant predictors:
  - **Reaction to routine changes**
  - **Pointing at desired objects**

---

## 📌 Key Contributions

- Built a reliable ASD prediction pipeline using behavioral data.
- Achieved high accuracy using ensemble models.
- Identified clinically relevant features through statistical analysis.
- Demonstrated machine learning’s potential for supporting early diagnosis.

---

## 🧠 Tools & Technologies

- **Languages**: Python
- **Libraries**: Scikit-learn, Pandas, Matplotlib, Seaborn
- **Platforms**: Jupyter Notebook, Google Forms, MS Excel
- **Additional Tools**: ROC Curve, Confusion Matrix, Feature Importance Plots

---

## 🧾 Research Paper

You can download and read the full research paper [here](.Research Conference Paper.pdf).  
*(Upload your PDF in the repo and rename accordingly)*

---

## 👥 Team Members

- Syed Huzaifa Bin Khamis  
- Haseeb Ahmad  
- Fahad Azeem  

**Supervisor**: Dr. Syed Faisal Bukhari

Department of Data Science  
Faculty of Computing and Information Technology  
University of the Punjab, Lahore

---

## 📬 Contact

For any queries or collaboration opportunities:

📧 syedhuzaifabinkhamis888830@gmail.com  
🔗 [GitHub](https://github.com/Syed-Huzaifa-coder)  
🔗 [LinkedIn](https://www.linkedin.com/in/syed-huzaifa-bin-khamis-522626323/)

---

## 📢 Citation

If you use or reference this work, please cite it as:

> *Huzaifa, S., Ahmad, H., & Azeem, F. (2025). Early Prediction of Autism Spectrum Disorder using Machine Learning. PUCIT Final Year Project Phase 1.*

---

