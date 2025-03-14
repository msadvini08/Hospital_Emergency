 # Hospital Emergency Room (ER) Data Analysis Report using POWER BI

## **1. Introduction**
Emergency rooms (ERs) are critical healthcare facilities that handle patient admissions, treatment, and hospital referrals. This project aims to analyze **Hospital ER data** to identify **trends in patient demographics, department referrals, admission rates, and satisfaction scores**. Using **Power BI**, the data has been visualized for actionable insights, which can help improve **ER efficiency and patient care**.

## **2. Objectives**
- Identify **patient admission trends** and **demographics**.
- Analyze **waiting times and operational efficiency** in ER.
- Evaluate **department referral distribution**.
- Measure **patient satisfaction scores**.
- Provide **interactive dashboards** for real-time healthcare analytics.

## **3. Dataset Overview**
### **3.1 Data Source**
- Kaggle: https://www.kaggle.com/datasets/xavierberge/hospital-emergency-dataset

### **3.2 Key Columns**
| Column Name            | Description                                       |
|-----------------------|-------------------------------------------------|
| Patient ID           | Unique identifier for each patient               |
| Admission Date       | Date and time of ER visit                        |
| Patient Gender       | Gender of the patient (M/F/Other)                |
| Patient Age         | Age group of the patient                         |
| Patient Race        | Ethnic background                                |
| Department Referral | Hospital department referred to (e.g., Orthopedics, General Practice) |
| Admission Flag      | Boolean flag indicating patient admission status |
| Patient Satisfaction Score | Rating of the patient's ER experience (scale 1-10) |

## **4. Data Analysis & Insights**
### **4.1 ER Admission Trends**
- **Daily and Monthly Admission Analysis**: Identifies peak hours and seasonal trends in ER visits.
- **Patient Inflow Variation**: Helps in optimizing hospital staffing and resource allocation.
- **Total Patients in January 2024:** 513
- **Total Patients (April 2023 - October 2024):** 9,216

### **4.2 Departmental Referrals**
- **Most Common Referrals:** General Practice (1,840 cases), Orthopedics (995 cases), Physiotherapy (276 cases), Cardiology (248 cases).
- **Patients Without Referrals:** 5,400 cases.

### **4.3 Admission vs. Discharge Rate**
- **January 2024:** 52.44% Admitted, 47.56% Not Admitted.
- **Overall (April 2023 - October 2024):** 50.04% Admitted, 49.96% Not Admitted.

### **4.4 Patient Demographics Analysis**
- **Gender Split (Jan 2024):** 46.98% Male, 53.02% Female.
- **Age Group Distribution (Jan 2024):** Most patients fall in the **0-9, 50-59, and 60-69** age brackets.
- **Largest Racial Groups:** White (2,571), African American (1,995), Multiracial (1,557), Asian (1,060).

### **4.5 Waiting Period & Operational Efficiency**
- **Average Wait Time (Jan 2024):** 36.3 minutes.
- **Average Wait Time (Overall):** 35.3 minutes.
- **Patients Seen Within 30 Minutes:** 61.6% (Jan 2024), 59.32% (Overall).

### **4.6 Patient Satisfaction Scores**
- **January 2024 Score:** 4.96 / 10.
- **Overall Satisfaction Score:** 4.99 / 10.

## **5. Power BI Dashboard Features**
- **Interactive Filters & Slicers** for exploring different variables.
- **KPI Indicators** for hospital efficiency.
- **Visual Representations**:
  - **Bar Charts** (Department referrals, admissions, and demographics)
  - **Line Graphs** (Trends over time)
  - **Pie Charts** (Satisfaction score distributions)
  -**Heatmaps** (Patient visit timing analysis)
    
- **Screenshots of Power BI Dashboards:**
  ![Monthly view](https://github.com/user-attachments/assets/2c305c80-37a5-4756-a1dd-c81da5e07872)
  ![Consolidated View](https://github.com/user-attachments/assets/5b6bc354-9f48-4679-94d7-efeecc579fd6)
  ![Patient Details](https://github.com/user-attachments/assets/ac9bb539-fcea-4e97-be0c-3c464cc077fd)
  ![Key Takeaways](https://github.com/user-attachments/assets/39ea6ffa-855b-4053-ada1-0dee024315c9)


## **6. Technologies Used**
- **Power BI** – Interactive visualization and dashboard creation.
- **Power Query** – Data transformation and cleaning.
- **DAX (Data Analysis Expressions)** – Custom calculations for insights.
- **CSV/Excel** – Data storage and processing.

## **7. Conclusion & Recommendations**
- **Peak ER hours require optimized staffing & resource management.**
- **High waiting times indicate areas needing workflow improvement.**
- **Departmental referrals help in managing hospital workload effectively.**
- **Satisfaction scores highlight patient service gaps that need attention.**
- **Saturdays, Thursdays, and Sundays are the busiest days, requiring extra staffing.**

## **8. Future Scope**
- **Integration with real-time hospital systems** for dynamic insights.
- **Predictive analytics using Machine Learning** to forecast ER admission trends.
- **Enhanced patient tracking and personalized treatment recommendations.**

---
**Author:** *Manisadvini Bolla*  


