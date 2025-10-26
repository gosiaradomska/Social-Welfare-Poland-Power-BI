# Social Welfare in Poland (2019-2023) - Power BI Dashboard

### [Click Here for a Short Video Demonstration of the Dashboard](https://youtu.be/PZGjMecnpD4)

## Project Overview

This repository contains an interactive Power BI dashboard that visualizes some aspects of the **social welfare** system in Poland for the years 2019-2023.

The primary goal of this project is to consolidate complex data into a clear, interactive, and easy-to-understand format. The dashboard allows users to explore trends and regional differences across various social welfare categories.

**Data Source:** All data used in this report comes from the official **Local Data Bank (BDL)** provided by **Statistics Poland (GUS)**.

## Dashboard Preview

The dashboard is built from four main pages, each focusing on a specific, official GUS category:

1.  **Beneficiaries of Social Assistance at Domicile:** Analyzing the demographics of beneficiaries by age, household income, and main source of livelihood.

  ![Beneficiaries of Social Assistance at Domicile](https://github.com/user-attachments/assets/8df6c51a-41b7-4ee3-b69e-e7af09749d80)

2.  **Social Assistance Benefits:** Visualizing the value and types of benefits paid, distinguishing between monetary and non-monetary aid.

![Social Assistance Benefits](https://github.com/user-attachments/assets/9ae3bd0a-923f-486c-bb86-79a840fd8881)
   
3.  **Institutional Foster Care:** A detailed look at institutional care facilities, including the number of places, residents, and primary reasons for placement.

![Family Foster Care](https://github.com/user-attachments/assets/d6f42428-3790-4a3a-92b5-c2e318fd3195)

4.  **Family Foster Care:** An analysis of family-based foster care, including types of families and demographics of children in care.

![Institutional Foster Care](https://github.com/user-attachments/assets/17a2308c-2e49-4016-b972-68a341f4d317)


## Key Features

* **Interactive Visuals:** Key visuals on each page are interactive, allowing users to click on chart elements to dynamically cross-filter other elements on the page.
* **Drill-Down Capabilities:** Users can filter the entire report by **Year** and **Voivodeship (Region)** using the slicers on the left.
* **Diverse Visualizations:** The report uses a variety of charts (maps, treemaps, bar, pie, donut) to best represent the data.
* **Clear KPI Cards:** Key metrics are displayed prominently for an at-a-glance understanding.

## Technologies Used

* **Power BI Desktop:** Used for data import, transformation, modeling, and visualization.
* **Power Query (M):** Used for cleaning and preparing the data from BDL.
* **DAX:** Basic DAX was used for creating simple measures and calculations.

## Repository Contents

* **`Dashboard_PS.pbix` File:** The full Power BI project file.
* **`/data`:** Folder containing the raw `.xlsx` files downloaded from BDL.
* **`/screenshots`:** Folder containing the dashboard preview images.
