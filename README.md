
# 🚀 Data Preprocessing for Machine Learning – Titanic Dataset

This project is part of the **Codveda Machine Learning Internship – Task 1**, focusing on preparing raw data for ML models using the **Titanic dataset**.

---

## 📌 Task Objectives

- ✅ Handle missing data
- ✅ Encode categorical variables
- ✅ Normalize numerical features
- ✅ Split dataset into training and testing sets

---

## 📊 Dataset Description

The dataset used is the classic **Titanic dataset**, containing information about passengers like:
- Name, Age, Gender, Ticket Fare, Embarked Port, etc.
- Target: **Survived** (0 or 1)

---

## 🔧 Tools & Libraries

- Python
- Pandas
- Scikit-learn
- LabelEncoder
- StandardScaler
- train_test_split

---

## 🧪 Key Preprocessing Steps

1. **Missing Values:**
   - Filled `Age` with mean value
   - Dropped `Cabin` (highly sparse)
   - Filled `Embarked` with mode

2. **Categorical Encoding:**
   - `Sex` encoded with `LabelEncoder`
   - `Embarked` encoded using One-Hot Encoding

3. **Feature Scaling:**
   - Standardized `Age` and `Fare` using `StandardScaler`

4. **Train-Test Split:**
   - Features `X` and Target `y` were split using `train_test_split`

---

## 📂 Output

- Preprocessed dataset ready for model training
- Clean, encoded, and scaled features
- Train and test sets prepared

---

## ✅ Status

✔️ **Completed as Task 1** of the Codveda ML Internship  
🔗 [Add your GitHub notebook or script link here]

---

## 🔖 Tags

#CodvedaJourney #CodvedaExperience #FutureWithCodveda #MachineLearning #TitanicDataset #DataPreprocessing
