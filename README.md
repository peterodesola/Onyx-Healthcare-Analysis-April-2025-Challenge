## 📚 Table of Contents

1. [🩺 Healthcare Data Analysis Dashboard (Power BI Project)](#-healthcare-data-analysis-dashboard-power-bi-project)
2. [📌 Overview](#-overview)
3. [📥 Dataset Information](#-dataset-information)
4. [🛠️ Tools & Technologies](#️-tools--technologies)
5. [🔍 Objectives](#-objectives)
6. [🧪 Methodology](#-methodology)
   - [Data Cleaning & Transformation](#1-data-cleaning--transformation)
   - [Data Modeling](#2-data-modeling)
   - [Dashboard Design](#3-dashboard-design)
7. [📊 Dashboard Pages & Key Insights](#-dashboard-pages--key-insights)
   - [Page 1: Healthcare Overview](#-page-1-healthcare-overview)
   - [Page 2: Medical Insights](#-page-2-medical-insights)
   - [Page 3: Insurance & Financials](#-page-3-insurance--financials)
8. [💡 Recommendations](#-recommendations)
9. [🌐 Live Demo](#-live-demo)
10. [📎 Contact](#-contact)





# 🩺 Healthcare Data Analysis Dashboard (Power BI Project)

## 📌 Overview

This project explores patient demographics, medical conditions, financial billing, and insurance trends using an interactive **Power BI dashboard**. The dataset is sourced from **Onyx Data's Healthcare Challenge** and demonstrates how data visualization can support evidence-based healthcare decisions.

---

## 📥 Dataset Information

- **Source**: [Onyx Data – Power BI Challenge](https://www.onyxdata.co.uk/)
- **Data Types**: Patient records, hospital visits, medical conditions, billing, insurance, and test results
- **Size**: 50K+ patient records
- **Time Period**: 2019 – 2024

---

## 🛠️ Tools & Technologies

| Tool       | Purpose                      |
|------------|------------------------------|
| Power BI   | Data modeling & visualization|
| Power Query| Data cleaning & transformation|
| DAX        | Calculated fields & measures |

---

## 🔍 Objectives

- Analyze key healthcare metrics across hospitals
- Uncover trends in billing, test results, and insurance
- Identify top health conditions and medications
- Provide actionable insights for healthcare optimization

---

## 🧪 Methodology

### 1. Data Cleaning & Transformation
- Checked for duplicates and nulls
- Derived fields:
  - `Admission Year`
  - `Billing Category`
  - Ranked top conditions with `RANKX`

### 2. Data Modeling
- Defined table relationships (Hospital, Patient, Insurance)
- Created Measures:
  - `Total Billing Amount`
  - `Avg Billing`
  - `Patient Count`
  - `Avg Length of Stay`

### 3. Dashboard Design
- Interactive report with **3 pages**
- Used **slicers**, **tooltips**, **drill-downs**, and **bookmarks**
- Visual aesthetics follow a medical blue-green theme

---

## 📊 Dashboard Pages & Key Insights

### 📍 Page 1: Healthcare Overview
- **KPIs**:
  - 💰 Total Billing: `$1.42B`
  - 👤 Total Patients: `56K+`
  - 💊 Avg Billing per Patient: `$25.5K`
  - 🏥 Avg Length of Stay: `15.5 days`
- **Visuals**:
  - Top 5 Conditions (Diabetes, Hypertension, etc.)
  - Gender Split
  - Blood Type Test Results
  - Geographic distribution map
![healthcare overview dashboard](https://github.com/user-attachments/assets/b573edb3-6a41-4b66-9011-e1f15f125484)



### 📍 Page 2: Medical Insights
- Top 5 Medications: Lipitor, Ibuprofen, etc.
- 55% of test results are **abnormal**
- Female patients show higher condition counts
- Treemap of billing by condition
![medical insight](https://github.com/user-attachments/assets/43cd1ab9-3d2a-4a7a-a0a0-c108e34f0944)


  
### 📍 Page 3: Insurance & Financials
- Billing trends from **2019–2024**
- Top insurance: **Medicare**
- Houston Methodist is the highest-billing hospital
![financial summary](https://github.com/user-attachments/assets/2f385f7a-8259-4725-8c08-53a1afc4a4c5)



---

## 💡 Recommendations

- Focus on chronic condition **prevention** (Hypertension, Diabetes)
- Invest in **digital health monitoring** to reduce hospital stay length
- Enhance **patient screening** to improve test result outcomes
- Allocate more resources to high-traffic hospitals

---


---

## 🌐 Live Demo

> ⚡ *This dashboard is available as a Power BI .pbix file. Reach out via [LinkedIn](https://www.linkedin.com/) to request access or view the static images above.*
> You can also visit Power Bi link to see the interactive dashboard via [https://app.powerbi.com/view?r=eyJrIjoiMDk1OTNkMDgtMTE2Ny00ZDdlLWEwM2QtMTIwYzg4NjRhN2QwIiwidCI6IjQ2NTRiNmYxLTBlNDctNDU3OS1hOGExLTAyZmU5ZDk0M2M3YiIsImMiOjl9](https://app.powerbi.com/view?r=eyJrIjoiMDk1OTNkMDgtMTE2Ny00ZDdlLWEwM2QtMTIwYzg4NjRhN2QwIiwidCI6IjQ2NTRiNmYxLTBlNDctNDU3OS1hOGExLTAyZmU5ZDk0M2M3YiIsImMiOjl9)

---

## 📎 Contact

**Analyst:** _Peter Odesola_  
**LinkedIn:** [linkedin.com/in/peterodesola](https://linkedin.com/in/peterodesola)  
**GitHub:** [github.com/peterodesola](https://github.com/peterodesola)  

---

> ✅ *Thank you for viewing this project! Feel free to fork, star ⭐, or give feedback.*

