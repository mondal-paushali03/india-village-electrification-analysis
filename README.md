# India Village Electrification Analysis & Dashboard

![image](https://github.com/user-attachments/assets/d4d457a2-8e6d-4d57-b0fb-c12df3a668e7)


This project provides a data-driven analysis and interactive dashboard detailing the status of village electrification across India's States and Union Territories as of May 2025. The goal is to present key insights into national progress and identify regions for targeted intervention.

## 📊 Key Findings

* **National Status:** As of May 2025, **83.67% of India's villages are electrified** (497K out of 594K).
* **Leading States:** States such as **Karnataka and Madhya Pradesh** show high rates of village electrification.
* **Focus Areas:** Efforts are concentrated in **Jharkhand, Bihar, and Orissa**, which currently have the lowest electrification rates.

## 🛠️ Analytical Approach

This project followed a structured data analysis pipeline:

1.  **Data Sourcing & Cleaning:**
    * Acquired raw village electrification data from the **Open Government Data (OGD) Platform India**.
    * Utilized **Python (Pandas)** for data cleaning, including handling inconsistencies, standardizing names, and ensuring data integrity.
    * **Derived Columns:**
        * `Unelectrified Villages`: Calculated as `Total Villages - Electrified Villages`. Used to identify remaining work.
        * `Percentage of Villages Electrified`: Calculated as `(Electrified Villages / Total Villages) * 100`. Used for comparative analysis across states.

2.  **Exploratory Data Analysis (EDA):**
    * Conducted EDA to identify patterns, understand data distributions, and guide visualization design.

3.  **Interactive Dashboard Development:**
    * Developed the dashboard using **Microsoft Power BI / Tableau**.
    * **Applied Filters:**
        * `Filter By State/UT`: Allows selection of specific regions.
    * Designed visuals (gauge, line, bar charts, choropleth map) to effectively communicate findings and support interactive data exploration.

## 💻 Technologies Used

* **Data Processing & Analysis:** Python (Pandas)
* **Data Visualization & Dashboarding:** Microsoft Power BI 
