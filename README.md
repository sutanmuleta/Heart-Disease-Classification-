# Heart Disease EKG Prediction – Scenario and Impact Analysis

## Project Overview

This project uses a **classification neural network model** to predict whether a patient’s **electrocardiogram (EKG)** result is normal or abnormal.  
I used the **UCI Heart Disease dataset** and tested how real-world changes in patient data would affect the model’s predictions.

---

## What I Did

### 1️⃣ Model Training

- Trained a **classification model** using patient features like age, blood pressure, and cholesterol.
- Target: Predict if the **EKG result is normal or abnormal**.

---

### 2️⃣ Scenario Analysis

I created **3 real-world scenarios** to see how the model reacts when health features change:

| Scenario | What Changed | Why |
|-----------|--------------|-----|
| **Aging Population** | Age +10 years | To simulate older patients |
| **Healthier Lifestyle** | Blood Pressure -10% | To simulate better health habits |
| **Economic Stress** | Cholesterol +20% | To simulate the effects of poor diet and stress |

---

### 3️⃣ Sensitivity Analysis

I tested how sensitive the model is to **age** vs **cholesterol** changes.  
**Result:**  
- **Age** → Strong impact on predictions  
- **Cholesterol** → No impact on predictions  

---

## Results Summary

- **More abnormal EKG predictions when patients are older**
- **Slight increase in abnormal EKG predictions even when lowering blood pressure (unexpected)**
- **No change in predictions when cholesterol increases**

---

## Project Files

| File | Description |
|------|-------------|
| `Heart_Disease_Scenario_Analysis.ipynb` | Full notebook with code, scenarios, and predictions |
| `README.md` | This file |
| `Scenario_Analysis_Report.docx` | Word document summary with screenshots and conclusions |

---

## How to Run

Make sure you have:

- Python  
- TensorFlow / Keras  
- Pandas  
- Scikit-learn  

Run the notebook in **Jupyter** or **Google Colab**.

---

## Author

**Sutan Tadese**  
Student Project – Beginner Level AI & Data Science
