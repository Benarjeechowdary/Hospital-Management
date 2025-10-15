# Hospital Analytics Project

![Hospital Building](https://images.unsplash.com/photo-1586773860418-d37222d8fce3?ixlib=rb-4.0.3&q=80&fm=jpg&crop=entropy&cs=tinysrgb&w=1080)

## Overview

A data analytics project focused on hospital operations, based on a comprehensive dataset of hospital patients, departments, staff, and bed occupancy. The repository includes data exploration, transformation and visualization steps, culminating in a single-page Power BI dashboard for stakeholders.

---

## Project Structure

| File                    | Description                                |
|-------------------------|--------------------------------------------|
| Hospital.xlsx           | Raw data including patients, staff, beds, and departments |
| Hospital-EDA.ipynb      | Jupyter Notebook for data analysis and preparation |
| Power BI Dashboard      | Single-page dashboard for summary insights (not included here) |

---

## Data Sources

The main data is provided in `Hospital.xlsx` with information on:
- Patient and visit details (ID, age, location, gender, type, treatment cost, length of stay, feedback)
- Department and staff information
- Bed status and assignment

---

## Data Preparation

All data merging and cleaning operations are carried out in `Hospital-EDA.ipynb`:
- Loading and merging sheets from the Excel file
- Cleaning missing values and checking for duplicates
- Transforming columns to the correct types (dates, numeric)
- Generating summary features and exporting the cleaned dataset for visualization

---

## Key Analyses

The notebook and dashboard address:
- Monthly patient admissions trends
- Revenue and cost breakdowns by month and department
- Patient demographic distributions (age, city, state, gender)
- Patient feedback and rating summaries
- Key metrics (average treatment cost, length of stay, bed occupancy)
- Relationship between satisfaction score and cost

---

## Power BI Dashboard

The dashboard (single page) displays the following:
- Patient and revenue trends over months
- Departmental breakdown of revenue and admissions
- Age, gender, location profiles
- Feedback and satisfaction ratings
- Main KPIs with filter/slicer options

---

## How to Use

1. Update or extend `Hospital.xlsx` as needed.
2. Run `Hospital-EDA.ipynb` to merge, clean, and analyze the raw data. Export the output for Power BI if updates are made.
3. Import the cleaned data into Power BI. Utilize or adapt the dashboard to the needs of your stakeholders.
4. Use the dashboard for decision-making in hospital administration, planning, or reporting.

---

## Authors

- Data preparation: as documented in `Hospital-EDA.ipynb`
- Dashboard and analytics: as implemented in Power BI

---

## Notes

- Do not rename columns or sheets: this may break merging code or dashboard visuals.
- For modifications, update both the notebook and dashboard files as required.

