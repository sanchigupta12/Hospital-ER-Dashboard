# 🏥 Hospital Emergency Room Dashboard

This project presents an interactive **Power BI dashboard** designed to monitor and analyze key performance metrics for a hospital's Emergency Room (ER). The dashboard visualizes insights on patient volume, wait times, admission rates, referral departments, and demographics to support data-driven decision-making.

![Dashboard Screenshot](assets/hospital.jpg)

---

## 📊 Key Features

- Tracked critical ER KPIs such as:
  - Number of patients
  - Average wait time
  - Satisfaction scores
  - Referral departments
  - Admission status breakdown
- Visualized time-based trends using line charts, bar graphs, and heatmaps
- Designed with a monthly view filter for time-based comparison
- Enhanced decision-making through interactive slicers and responsive layout

---

## 🔧 Tech Stack

| Tool            | Purpose                                 |
|-----------------|------------------------------------------|
| **Power BI**    | Data visualization, DAX KPIs             |
| **Power Query** | Data cleansing and transformation (ETL)  |
| **BigQuery**    | Cloud data storage and access layer      |
| **DAX**         | Custom measures for performance metrics  |

---

## ⚙️ Workflow

1. **Data Acquisition**: ER dataset downloaded and loaded into Google BigQuery
2. **Integration**: Connected BigQuery with Power BI using built-in connector
3. **ETL**: Cleaned and transformed the data using Power Query Editor
4. **Modeling & DAX**: Built DAX measures for metrics like avg. wait time, satisfaction, and referrals
5. **Dashboard Design**: Created a responsive and accessible layout for healthcare stakeholders

---

## 📌 Sample KPIs

-  Total Patients: `431`
-  Average Wait Time: `36.7 mins`
-  Patient Satisfaction Score: `4.72 / 5`
-  Department Referrals: Bar graph of specialties (e.g. ortho, cardio)
-  Demographics: Gender, race, and age group breakdown


