# 🏥 Healthcare Appointment No-Show Prediction

## 📌 Project Overview

This project aims to predict whether a patient will show up for their scheduled medical appointment using machine learning. Missed appointments (no-shows) cost healthcare systems time and money, and predictive analytics can be used to optimize scheduling and improve efficiency.

We use Python (with scikit-learn, pandas) to build the predictive model.

---

## 🎯 Objective

- Predict no-show appointments based on patient demographics and appointment details.
- Identify key factors influencing no-shows (age, SMS reminders, weekday, etc.).

---

## 🛠️ Tools & Technologies

- **Language**: Python  
- **Libraries**: pandas, scikit-learn, matplotlib, seaborn
- **Development Environment**: Jupyter Notebook

---

## 📁 Dataset

- `appointments.csv`  
  Contains appointment data with features such as:
  - Patient ID
  - Appointment and scheduled dates
  - Gender, Age
  - SMS received
  - Health conditions
  - No-show status

> 📌 Note: Data cleaning involved removing negative ages and incorrect date values.

---

## 🧠 Model Development

### 1. **Data Preprocessing**
- Cleaned dataset: removed invalid entries
- Encoded categorical variables
- Engineered new features:
  - `waiting_days` between scheduled and appointment date
  - `age_group` and `appointment_weekday`

### 2. **EDA (Exploratory Data Analysis)**
- Analyzed trends:
  - Age vs No-show
  - SMS reminders vs No-show
  - Appointment day impact

### 3. **Model Training**
- Used a **Decision Tree Classifier**
- Applied **GridSearchCV** for hyperparameter tuning

### 4. **Evaluation**
- Assessed with accuracy and classification report
- Visualized confusion matrix

### 5. **Individual Prediction**
- Function to test model on a single user input

---

## 📄 Report

A detailed PDF report includes:
- Introduction & Abstract
- Tools Used
- Step-by-step breakdown of the project
- Final conclusions

---

## ✅ How to Run

1. Clone the repository  
2. Open the Jupyter Notebook  
3. Run all cells to load, clean, and model the data  

---

## 🔮 Future Improvements

- Try advanced models (Random Forest, XGBoost)
- Add real-time prediction via web interface (e.g., Streamlit)
- Include socioeconomic or geographic data for deeper analysis

---

## 📬 Contact

For questions or collaboration opportunities:  
**Kirtan Shah**
