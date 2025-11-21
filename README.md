# ❤️ Heart Disease Prediction using Machine Learning

This project predicts the presence of heart disease using clinical features such as **chest pain type**, **resting blood pressure**, **cholesterol**, **maximum heart rate**, **ECG results**, and **exercise-induced angina**.  
It demonstrates an end-to-end Machine Learning pipeline suitable for healthcare analytics roles.

---

## 📌 Project Overview

This project covers:

- 📥 Data loading  
- 🧼 Data cleaning & preprocessing  
- 🔍 Exploratory Data Analysis (correlation heatmap)  
- 📊 Feature scaling using StandardScaler  
- ✂️ Train-Test split (80/20)  
- 🧪 Logistic Regression model  
- 🌲 Random Forest model (300 trees)  
- 📉 Evaluation using confusion matrix & classification report  

---

## 🗂️ Dataset

The dataset used is the **Heart Disease UCI Dataset**.  
If using the manually uploaded file:

`heart.csv`

---

## 🛠 Technologies Used

- **Python 3**  
- **Pandas**  
- **NumPy**  
- **Matplotlib**  
- **Seaborn**  
- **Scikit-learn**  
- **Google Colab**

---

## 📈 Model Performance

| Model                 | Accuracy |
|-----------------------|----------|
| Logistic Regression   | ~82–85%  |
| Random Forest (300 trees) | ~85–92%  |

Both models performed similarly because the dataset is small and contains strong predictive features such as chest pain type and oldpeak.

---

## 🔬 Key Insights

- 📌 **Chest Pain Type (cp)** is one of the strongest predictors.  
- 📌 **Maximum Heart Rate (thalach)** has a clear positive correlation.  
- 📌 **Oldpeak** and **Exercise-Induced Angina (exang)** show **negative but strong** correlation with target — meaning they still influence prediction heavily.  
- 📌 Simpler models (Logistic Regression) perform almost as well as complex models due to linear decision boundary.  

---

## 🩺 Healthcare Relevance

Heart disease is one of the most critical global health concerns.  
A predictive model like this helps in:

- Early risk detection  
- Screening high-risk patients  
- Preventive healthcare planning  
- Supporting clinical decision systems  

This type of project aligns closely with **Innovaccer’s mission of improving healthcare outcomes through data analytics**.

---

## 📁 Repository Structure

