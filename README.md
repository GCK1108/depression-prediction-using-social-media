# 🧠 Social Media Mental Health Prediction

This project analyzes social media usage patterns to identify early signs of depression using machine learning. Based on behavioral and psychological survey data, the system predicts whether a person is at **low** or **high** risk of depression.

---

## 📌 Project Overview
The goal of this project is to build a data-driven early warning system for mental health.  
The dataset includes various psychological and social media usage features, which are cleaned, transformed, explored, and used to train a binary classification model.

---

## 🔍 Features Used
- Age  
- Daily Social Media Usage Time  
- Distraction Score  
- Worry Score  
- Concentration Difficulty  
- Social Comparison  
- Sleep Issues  

These features collectively help determine the depression risk level.

---

## 🎯 Model Used
### Logistic Regression  
Logistic Regression was selected because:

- It is simple and interpretable  
- Ideal for binary classification  
- Performs well on structured survey data  
- Produces probability-based predictions  

The model predicts:
- **0 → Low Depression**
- **1 → High Depression**

---

## 📊 Model Performance
- **Accuracy:** ~84%  
- Strong performance in identifying high depression cases  
- Includes confusion matrix, classification report, and ROC-AUC score  

---

## 🛠️ Technologies Used
- Python  
- Jupyter Notebook  
- Pandas  
- NumPy  
- Matplotlib & Seaborn  
- Scikit-learn  

---

## 🚀 How to Use
1. Load the dataset (`.csv`).  
2. Run all preprocessing cells in the notebook.  
3. Train the model using Logistic Regression.  
4. Use the prediction script to check depression risk for a new user input.

**Example output:**

---

## 🏁 Conclusion
This project demonstrates how social media behavioral data can be effectively used to detect early mental health risks. With further enhancement (text analysis, real-time data, etc.), it can support mental-health monitoring systems.

