# COVID-19 Dashboard in Excel

## Project Overview

This project is an interactive **COVID-19 Dashboard** created in Excel to visualize and analyze state-wise and zone-wise statistics, including confirmed cases, deaths, discharge ratios, and population. The dashboard helps in quick decision-making and data-driven insights.

## Step-by-Step Walkthrough

### 1. Raw Data Preparation

* Added initial COVID-19 statistics in the **Data** sheet.
* Verified columns: `State`, `Zone`, `Confirmed`, `Deaths`, `Discharged`, `Population`.

### 2. State-Wise Calculations

* Created **State_Wise** sheet → Summarized confirmed cases, discharges, and deaths using a Pivot Table.
* Created **State-Wise-Death_Ratio** sheet → Added calculated column for death percentage.
* Created **State-Wise-Population** sheet → Compared population versus confirmed cases.

### 3. Zone-Wise Calculations

* Created **Zone_Wise_Death** sheet → Aggregated total deaths per zone.
* Created **Zone-Wise-Discharge-Ratio** → Calculated discharge ratio.
* Created **Zone-Wise-Population** → Summarized population data zone-wise.

### 4. Building the Dashboard

* Inserted charts (column, bar, pie) from state-wise and zone-wise summaries.
* Added KPI metrics using formulas (`SUM` of confirmed, discharged, deaths).
* Inserted slicers for filtering by `State` and `Zone`.
* Applied consistent formatting: chart titles, axis labels, gridlines, and color-coding for better readability.
* Final layout arranged in **DashBoard** sheet for a clean, professional look.


## Tools Used

* Microsoft Excel (Pivot Tables, Charts, Formulas, Slicers)


## Representation of DashBoard


 https://github.com/user-attachments/assets/73f64c8a-b7e2-4c69-96a0-b93a8c04624a


