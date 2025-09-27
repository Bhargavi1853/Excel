# Excel

A collection of projects built using Microsoft Excel, showcasing skills in data cleaning, pivot tables, dashboards, and data visualization.

---

# COVID-19 Impact Analysis Dashboard (Excel)

## Introduction

The objective of this project was to design an interactive **COVID-19 Dashboard in Excel** that provides insights into **state-wise and zone-wise confirmed cases, deaths, discharge ratios, and population distribution**.

The dashboard serves as a **visual representation of the pandemic’s impact** across different regions, enabling users to analyze patterns, compare regions, and make informed decisions quickly.

---

## 📂 Dataset

* The raw dataset is stored in the **`Data`** sheet.
* Columns include:

  * **State**
  * **Zone**
  * **Confirmed Cases**
  * **Deaths**
  * **Discharged Cases**
  * **Population**

Data was cleaned, structured, and prepared for further analysis.

---

## ⚙️ Steps Involved

### **Step 1: Importing & Cleaning Data**

* Imported COVID-19 dataset into Excel.
* Ensured consistent headers.
* Removed inconsistencies and missing values.
* Structured columns for states, zones, confirmed, discharged, deaths, and population.



### **Step 2: State-Wise Analysis**

* **State_Wise** sheet: Created Pivot Tables to summarize state-wise cases.
* **State-Wise-Death_Ratio**:

           Death Ratio (%) = (Total Deaths / Total Active Cases) * 100
  
* **State-Wise-Population**: Compared COVID-19 spread with population density.



### **Step 3: Zone-Wise Analysis**

* **Zone_Wise_Death**: Total deaths aggregated per zone.
* **Zone-Wise-Discharge-Ratio**:
  
           Discharge Ratio (%) = ( Total Discharged / Total Active Cases​) × 100
  
* **Zone-Wise-Population**: Summarized population distribution per zone.



### **Step 4: Dashboard Creation**

* Built the final **DashBoard** sheet with:

  * **KPIs**: Total Confirmed, Deaths, and Discharged.
  * **Charts**:

    * Bar/Column charts (state-wise cases, deaths, discharge ratios)
    * Pie/Donut charts (zone-wise population vs cases)
  * **Slicers**: Interactive filtering by **State** and **Zone**.
* Applied consistent formatting: chart titles, legends, color coding, and layout for readability.

---

## 📊 Dashboard Features

* Interactive **state & zone-level insights**
* Dynamic **death ratio & discharge ratio calculations**
* **Population vs cases analysis**
* Professional **visualization using charts, slicers, and KPIs**

---

## ✅ Conclusion

The **COVID-19 Dashboard** provides an **interactive and visual summary** of pandemic statistics across states and zones. By integrating raw data, calculated ratios, and professional dashboards, the project ensures **clarity, scalability, and accuracy**.

This project demonstrates practical skills in:

* Data cleaning
* Pivot Tables & Formulas
* Data Visualization in Excel
* Dashboard design for decision-making

---

## 🛠️ Tools Used

* **Microsoft Excel**

  * Pivot Tables
  * Pivot Charts
  * Slicers
  * Data Cleaning & Formulas

---

## Sample Dashboard Preview

<img width="1840" height="686" alt="Screenshot 2025-09-27 164609" src="https://github.com/user-attachments/assets/99c3aab2-9d0f-4679-86f3-ecbc2b4b6d7f" />

---

## 🚀 Future Improvements

* Automating dataset refresh using Power Query.
* Adding trend analysis over time.
* Integrating external COVID-19 APIs for real-time updates.

