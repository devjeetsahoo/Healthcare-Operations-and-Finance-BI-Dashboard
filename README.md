# Healthcare-Operations-and-Finance-BI-Dashboard🏥 

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-025E8C?style=for-the-badge&logo=sql&logoColor=white)
![Excel](https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)

A comprehensive Power BI dashboard designed to provide a 360-degree view of hospital operations. This project leverages data from SQL and Excel to deliver actionable insights for hospital administrators, doctors, and financial analysts. The dashboard focuses on key performance indicators across patient care, hospital resources, doctor performance, and financial health.

---
## Dashboard Overview
<img width="1316" height="737" alt="Image" src="https://github.com/user-attachments/assets/5a1ce901-2230-4ce6-9280-98ed5f564a71" />


## ✨ Key Features

* **Holistic Overview:** A high-level summary of all critical hospital metrics.
* **Patient Analysis:** Detailed patient demographics, treatment history, billing, and medicine tracking.
* **Doctor Performance:** In-depth analysis of doctor schedules, patient load, commissions, and ratings.
* **Hospital Resource Management:** Real-time tracking of bed occupancy, surgeries, and laboratory test statuses.
* **Financial Insights:** A dedicated module for revenue analysis, expense tracking, medicine inventory, and supplier management.
* **Interactive & User-Friendly:** A modern, clean UI with intuitive navigation and interactive data filtering.

---

## 📊 Dashboard Showcase

Here's a look at the different modules within the dashboard. To embed your images, replace the `` placeholders with the actual URLs or relative paths to your screenshots in the repository.

| Dashboard View                                                                                                   | Description                                                                                                                                                                                            |
| :--------------------------------------------------------------------------------------------------------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Analysis Overview**<br/>                                                  | The landing page provides a high-level, bird's-eye view of the entire hospital's operations, serving as a gateway to more detailed insights.                                                            |
| **Patient Overview**<br/>                                                     | A summary dashboard focusing on patient-centric data like admissions, discharge rates, upcoming appointments, and overall medicine consumption trends.                                                     |
| **Detailed Patient Profile**<br/>                                           | Drills down into a specific patient's record, showing personal details, diagnosis, treatment ratings, admission/discharge dates, and a complete breakdown of charges and medicines bought.                |
| **Doctor's Dashboard**<br/>                                                           | A personalized dashboard for doctors to view their appointments, patient feedback, and financial performance, including a dynamic commission calculator.                                                     |
| **Hospital Information**<br/>                                             | This module focuses on the hospital's internal resources, providing analytics on patient distribution by age, bed occupancy rates (General, Private, ICU), surgery schedules, and patient test results.      |
| **Finance Dashboard**<br/>                                                      | A comprehensive financial overview, detailing key metrics like paid amounts, salaries, and commissions. It includes breakdowns of charges, payment methods over time, medicine stock vs. sales, and supplier data. |

---

## 🛠️ Tech Stack & Data Architecture

This project was built using a combination of powerful data tools:

* **Backend & Data Storage:**
    * **SQL:** Used for robust data storage, management, and querying of transactional data like patient records, appointments, and billing.
    * **Microsoft Excel:** Utilized for supplementary data, master lists (e.g., doctor specializations, medicine prices), and potentially for initial data staging.

* **Business Intelligence & Visualization:**
    * **Microsoft Power BI:** The core tool for creating the interactive and visually rich dashboard. It connects to the SQL database and Excel files to model and visualize the data.

### Data Workflow

The data flows from its source to the final visualization in a structured manner:

1.  **Data Source:** Raw data is maintained in an **SQL Database** and supplemented with data from **Excel** files.
2.  **Data Modeling & Transformation:** **Power Query** within Power BI is used to extract, transform, and load (ETL) the data. This step involves cleaning data, establishing relationships between tables (e.g., Patients, Doctors, Appointments), and creating calculated columns and measures using **DAX** (Data Analysis Expressions).
3.  **Data Visualization:** The processed data is then visualized in **Power BI Desktop**, where the various charts, tables, and KPI cards are designed to create the final interactive dashboard.

---

## 🚀 Getting Started

To run this project locally, you'll need Power BI Desktop installed.

### Prerequisites

* [**Microsoft Power BI Desktop**](https://powerbi.microsoft.com/en-us/desktop/)

### Installation & Setup

1.  **Clone the repository:**
    ```sh
    git clone [https://github.com/your-username/hospital-dashboard.git](https://github.com/your-username/hospital-dashboard.git)
    ```
2.  **Navigate to the project directory:**
    ```sh
    cd hospital-dashboard
    ```
3.  **Open the Power BI file:**
    * Open the `.pbix` file using Power BI Desktop.
4.  **Connect to Data Sources:**
    * When you first open the file, Power BI may ask you to configure the data source connections.
    * Point the connection to your local SQL server instance and the provided Excel files. You may need to update the credentials in `Transform data` -> `Data source settings`.

---
##Snapshots from the Dashboard

## Snapshots Section
<img width="1211" height="657" alt="Image" src="https://github.com/user-attachments/assets/e05b4fee-7852-4804-9f84-97b14d61f15a" />

<img width="1119" height="583" alt="Image" src="https://github.com/user-attachments/assets/7c0abc5f-e5b9-46ef-b3cb-7b50c49f5355" />


<img width="1213" height="676" alt="Image" src="https://github.com/user-attachments/assets/9456e370-0c72-4ed5-870b-9de505768d01" />


<img width="1227" height="680" alt="Image" src="https://github.com/user-attachments/assets/8823a579-bee1-4a72-8f21-7103cf303663" />
<img width="1223" height="682" alt="Image" src="https://github.com/user-attachments/assets/f9aaa57a-38b2-4553-91f7-f2e1e1ae6a50" />



## ©️ LICENSE

This project is licensed under the MIT License. See the `LICENSE` file for more details.
