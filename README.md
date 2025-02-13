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

- Total number of patients (Card)
- Percentage of people with heart disease (Card)
- Average age of patients (Card)
- **Donut chart** to illustrate gender distribution (male/female)
- **Bar chart** showing the distribution of patients by age groups
- **Pie chart** showing the relationship between ST slope and risk of heart disease
- **Line column** chart analyzing ST wave regression and its effect on the disease
- **Ribbon chart** comparing the effect of gender on the incidence rate

### **2. Analysis of Disease Factors**

- **Area chart**: showing the relationship between chest pain type and disease incidence
- **Line Chart**: showing heart rate correlation with disease
- **Column chart**:  ECG type and its link to disease presence
- **Heatmap**:  showing the connection between cholesterol, blood pressure, and heart disease
- **Card** displaying the Male-to-Female ratio

### **3. Detailed Patient Analysis**

- **Scatter chart**: showing age vs. cholesterol impact on disease
- **Donut chart**: showing high vs. normal blood sugar proportion
- **Card**:for Heart Risk Score analysis
- **Column chart**: of ST wave regression effect on disease
- **Column chart**: of exercise-induced angina and heart disease link
- **Table**: for high-risk patient identification

### **4. Interactive Dashboard**
- **Slicers:** Gender, Age Group, Blood Sugar, Chest Pain Type
- **Dynamic Visuals:** Filters adjust the graphs for deeper insights
- **Table View:** Detailed patient data with search & filtering

---
## 📏 DAX Measures Used
- **Heart_Risk_Score**: Custom metric to highlight high-risk patients.
- Percentage of Patients with Heart Disease
- Average Age Calculation
- Categorical Counts for Different Risk Factors
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

