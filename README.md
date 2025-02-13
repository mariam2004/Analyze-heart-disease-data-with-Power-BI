# Heart Disease Analysis - Power BI Project

## 📌 Overview
This project aims to analyze heart disease data using Power BI. It includes data preprocessing, visualization, and insights derived from various charts and measures.

---
## 🗃️ Data Preprocessing
### **Modifications Made to the Dataset:**
- **Replaced numerical values with categorical labels** for better understanding:
  - `cp` (Chest Pain Type):
    - 0 → Typical Angina
    - 1 → Atypical Angina
    - 2 → Non-anginal Pain
    - 3 → Asymptomatic
  - `sex`:
    - 0 → Female
    - 1 → Male
  - `fbs` (Fasting Blood Sugar):
    - 0 → Normal
    - 1 → High Blood Sugar
  - `restecg` (Resting ECG Results):
    - 0 → Normal
    - 1 → ST-T Wave Abnormality
    - 2 → Left Ventricular Hypertrophy
  - `slope` (ST Segment Slope):
    - 0 → Upsloping
    - 1 → Flat
    - 2 → Downsloping
  - `thal` (Thalassemia Type):
    - 0 → Normal
    - 1 → Fixed Defect
    - 2 → Reversible Defect
  - `exang` (Exercise-Induced Angina):
    - 0 → No
    - 1 → Yes

- **Cleaned missing values** and ensured all data types were correctly formatted.

---
## 📊 Visualizations & Insights
### **1. Overview Page**
**Columns Used:** `age`, `sex`, `target`
- **Key Metrics:**
  - Total number of patients
  - Percentage of patients with heart disease
  - Average age of patients
- **Charts:**
  - **Pie Chart**: Gender distribution
  - **Bar Chart**: Age group distribution

### **2. Analysis of Disease Factors**
**Columns Used:** `cp`, `fbs`, `restecg`, `thalach`, `chol`, `trestbps`, `slope`
- **Bar Chart**: Chest Pain Type vs. Disease presence
- **Line Chart**: Heart Rate vs. Disease
- **Stacked Bar Chart**: Blood Sugar Levels vs. Disease
- **Heatmap**: Cholesterol & Blood Pressure impact

### **3. Detailed Patient Analysis**
**Columns Used:** `slope`, `ca`, `thal`, `exang`
- **Stacked Bar Chart**: ECG Type vs. Disease
- **Horizontal Bar Chart**: ST Slope impact
- **Scatter Plot**: Age vs. Cholesterol impact

### **4. Interactive Dashboard**
- **Slicers:** Gender, Age Group, Blood Sugar, Chest Pain Type
- **Dynamic Visuals:** Filters adjust the graphs for deeper insights
- **Table View:** Detailed patient data with search & filtering

---
## 📏 DAX Measures Used
- **Heart_Risk_Score**: Custom metric to highlight high-risk patients.
- **Conditional Formatting**:
  - Colored `age` based on risk level.
  - Applied alert system for high cholesterol & heart rate.
- **KPIs:**
  - High-risk patient percentage
  - Average cholesterol of heart disease patients

---
## 🚀 Summary
This Power BI project provides insights into heart disease factors and patient distributions. The interactive dashboard allows easy exploration and data-driven decision-making.

---
### 💾 Repository Details
- Power BI File (`.pbix`)
- Dataset (`heart.csv`)
- Presentation (`.pptx`)
- ReadMe (`README.md`)

