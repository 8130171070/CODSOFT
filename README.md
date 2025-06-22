# 🚢 Titanic Survival Prediction

This project applies machine learning to predict whether a passenger on the Titanic survived or not, using features like age, gender, passenger class, fare, and more.

---

## 📌 Objective

Use the Titanic dataset to build a classification model that predicts survival outcome for each passenger based on available features.

---

## 📊 Project Workflow

### 1. Data Exploration (EDA)
- 🔹 Survival analysis by Gender (Bar Plot)
- 🔹 Survival analysis by Passenger Class (Count Plot)
- 🔹 Age Distribution Comparison (KDE Plot)

### 2. Data Cleaning
- ✅ Filled missing `Age` values with median
- ✅ Filled missing `Embarked` values with mode
- ✅ Dropped `Cabin` column due to excessive null values

### 3. Feature Engineering
- 🔁 Label Encoded `Sex`
- 🟦 One-Hot Encoded `Embarked` → created `Embarked_Q`, `Embarked_S`

### 4. Model Building
- 📈 Logistic Regression model using `scikit-learn`
- 🧠 Train/Test split (80/20)
- 🎯 Achieved accuracy: **XX.XX%** *(replace with actual accuracy)*

### 5. Model Evaluation
- ✅ Confusion Matrix (Heatmap)
- ✅ Classification Report (Precision, Recall, F1-Score)

### 6. Model Deployment
- 💾 Saved using `pickle` as `titanic_model.pkl`
- 🔁 Reloaded model successfully and made predictions

---

## 📁 Folder Structure

```
titanic_survival_prediction/
│
├── data/                  # Dataset files (CSV)
├── images/                # Plots (saved PNGs)
├── notebooks/             # Jupyter Notebook
├── titanic_model.pkl      # Saved model (pickle file)
├── titanic_model.py       # Final Python script (optional)s
└── README.md              # Project documentation
```

---

## 🧰 Tech Stack Used

- Python 3.x 🐍  
- Jupyter Notebook 📒  
- Pandas, NumPy  
- Seaborn, Matplotlib  
- Scikit-learn  
- Pickle (model saving)

---

## ✅ Summary

The logistic regression model performed well in predicting Titanic survival using essential features. EDA insights were used to drive feature selection, leading to decent accuracy and generalization.

---

## 👨‍💻 Author

**Naman Verma**  
📍 [LinkedIn](https://www.linkedin.com/in/naman-verma-520355303)  
📧 namanverma12480@gmail.com
