# Hospital Management Analytics

An interactive Tableau dashboard and four-part story exploring patient distribution, treatment costs, monthly cost trends, patient outcomes, and doctor treatment costs.

## Business objective

Help hospital management review patterns in patient volume, treatment costs, and recorded outcomes. The dashboard supports exploration of the available data; its charts describe patterns and do not establish their causes.

## Dashboard
## [Live Dashboard](https://public.tableau.com/app/profile/md.ziaul.haque2813/viz/Hospital_Management_Tableau_Dashboard/InteractiveDashboard)

The dashboard brings together:

- Patients by hospital region
- Treatment cost by department
- Patient outcome distribution
- Monthly treatment cost trend
- Doctors ranked by total treatment cost
- KPI cards for total treatment cost, average cost per patient, critical patient percentage, and total patients treated

Filters shown in the dashboard include hospital region, department, outcome, doctor name, and month of admission date.

## Story

The Tableau story presents four views:

1. **Patient Distribution**
2. **Department Cost Analysis**
3. **Outcome Analysis**
4. **Doctor Performance**

![Hospital Operations Insights dashboard](screenshots/dashboard.png)
## Findings

Based on the project dataset and the displayed dashboard:

- **260** patients were treated.
- Total treatment cost was approximately **$19.90M**.
- **West** had the largest patient count, with **61**.
- **Neurology** had the highest department treatment cost, at **$5.32M**.
- **July** had the highest displayed monthly treatment cost, at **$2.70M**; **October** had the lowest, at **$1.01M**.
- Outcomes were **89 Recovered (34.2%)**, **87 Under Treatment (33.5%)**, and **84 Critical (32.3%)**.
- **Dr. Roy** had the highest displayed doctor treatment cost, at **$3.90M**.
- In the underlying dataset, **South and West tied for the most Critical patients, with 20 each**. This count was calculated directly from the data; a separate chart is not required to report it.

Values are rounded as displayed in the dashboard.

## Project files

Add the files you want readers to access, for example:

- Tableau workbook (`.twbx` or `.twb`)
- Dashboard and story screenshots
- Project brief describing the business questions and findings

## Data and privacy

Before publishing, confirm that the dataset and Tableau workbook contain no real patient information or other data that should not be public. Tableau packaged workbooks (`.twbx`) can contain embedded data. Do not commit the raw CSV or an embedded workbook extract unless the data is approved for public sharing.

## Interpretation

Treatment cost alone does not measure care quality, patient complexity, or department efficiency. Patient counts alone do not establish staffing needs, capacity, or unmet demand. Use the findings as descriptive signals for further review alongside appropriate operational context.

## Tools

- Tableau
- CSV dataset
- GitHub
