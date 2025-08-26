# Hospital Emergency Room Dashboard - README

This README describes the Hospital Emergency Room Dashboard created in Power BI for visualizing and analyzing key operational metrics from the hospital’s emergency room. The dashboard offers comprehensive insights for the month of January 2023.


## Overview

The dashboard is designed to provide a clear, data-driven monthly view of hospital ER activity, enabling stakeholders to monitor performance, assess patient care standards, and make informed decisions. It consolidates multiple data categories into interactive charts, graphs, and summary cards.[1]


## Features

### Key Metrics
- **No. of Patients:** Total number of ER visits for January 2023.
- **Average Wait Time:** Displays the mean patient wait duration in minutes.
- **Patient Satisfaction:** Tracks the average satisfaction rating given by patients.
- **Patients Referred:** Number of patients referred to other departments or facilities.[1]

### Visualizations & Insights

- **Trends and Line Charts:** Visualization of weekly patient count and wait time fluctuations.
- **Patient Admission Status:** Horizontal bar chart showing count and percentage of patients admitted vs. not admitted.
- **Wait Time Distribution:** Donut chart illustrating how many patients waited <30 min or >30 min.
- **Patient Age Group Analysis:** Bar chart segmenting patients by age brackets (e.g., 0-9, 10-19, ... 100+).
- **Patient Gender Breakdown:** Donut/pie chart for male vs. female patients.
- **Department Referral:** Bar chart showing the number of referrals by department.
- **Patient Race Data:** Bar chart on patient racial demographics.[1]

### Interactive Filters
- **Month and Year Selection:** Slicers in the sidebar allow users to filter the dashboard by month and year for comparative trend analysis.[1]


## Usage Instructions

1. **Open in Power BI Desktop or Service:** Import the PBIX file and connect to the relevant hospital ER data source.
2. **Adjust Slicers:** Use slicers to select your desired month and year.
3. **Interact with Visuals:** Click on charts and bars for tooltip details or data filtering.
4. **Export/Share Reports:** Download static reports or share the dashboard via Power BI Service.



## Data Model

The dashboard uses structured ER patient data, including:
- Patient demographics (age, gender, race)
- Admission and referral status
- Wait times and satisfaction scores

Calculated columns (e.g., Age Group via DAX `SWITCH` formula) are used for categorizing and filtering data efficiently.


## Insights & Value

This dashboard empowers hospital administrators and clinical staff to:
- Monitor bottlenecks and improve wait times
- Understand patient demographics and satisfaction trends
- Optimize staffing and resource allocation based on admission and referral stats
- Make data-driven decisions for quality improvement initiatives


## Customization & Extensions

The dashboard layout and measures can be easily adapted to:
- Support additional timeframes or departments
- Integrate extra metrics like outcomes or costs
- Provide drill-through details for patient-level review
