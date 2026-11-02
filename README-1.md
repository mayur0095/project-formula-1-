# Formula 1 Race Intelligence Dashboard

A data analytics and visualization project built using **Tableau Desktop** and **Microsoft Excel** to explore Formula 1 race performance, drivers, teams, circuits, qualifying results, lap intelligence, and race strategy.

## Student Information

| Field | Details |
|---|---|
| Name | Mayur Patel |
| Enrollment Number | EN25CA3020110 |
| Institution | Medi-Caps University |
| Course | BCA |
| Project Type | Data Analytics & Visualization |

## Project Overview

Formula 1 data is spread across several categories, including drivers, teams, circuits, race outcomes, lap times, and qualifying performance. This project brings selected information together in Tableau so that users can explore racing performance through visualizations, comparisons, and dashboards.

The workbook contains two dashboards and 15 worksheets covering different aspects of Formula 1 racing.

## Objectives

- Connect the supplied Formula 1 Excel dataset to Tableau.
- Review data types, field names, and relationships between tables.
- Create visualizations for drivers, teams, circuits, race results, lap times, and qualifying performance.
- Combine worksheets into dashboards.
- Use filters and chart calculations to support interactive exploration.
- Validate relationships, aggregations, and dashboard usability.

## Tools and Technologies

- **Tableau Desktop** – data modeling, worksheets, calculated measures, and dashboards.
- **Microsoft Excel** – source dataset and sheet organization.
- **GitHub** – source control and project documentation.

## Dataset

The Tableau workbook uses an Excel source named `F1 Racing Project Dataset.xlsx`. The source workbook contains these sheets:

| Dataset sheet | Description |
|---|---|
| `race_results` | Race results and driver performance fields. |
| `championship_standings` | Season, driver, team, points, wins, and standings. |
| `circuits` | Circuit identifiers, locations, and circuit characteristics. |
| `lap_intelligence` | Lap-level information, lap times, and tyre-related fields. |
| `qualifying_results` | Qualifying performance and positions. |

> **Important:** The Tableau workbook currently refers to an Excel file at a local Windows path. You may need to reconnect the data source to the location of `F1 Racing Project Dataset.xlsx` on your computer. The Excel dataset must be available for the workbook to refresh correctly.

## Dashboards

The Tableau workbook contains two dashboards:

1. **F1 Race Intelligence Dashboard** – a visual overview of driver and team championship comparisons and race-performance information.
2. **F1 Race Performance Dashboard** – additional visual analysis of Formula 1 race performance.

## Worksheets and Visualizations

The workbook includes the following 15 worksheets:

1. F Race Duration Analysis
2. F1 Circuit Distance Analysis
3. F1 Driver Championship Points
4. F1 Driver Reliability Analysis
5. F1 DRS Overtakes Analysis
6. F1 Fastest Lap Analysis
7. F1 Pit Stop Analysis
8. F1 Positions Gained Analysis
9. F1 Qualifying Performance
10. F1 Racing by Country
11. F1 Safety Car Analysis
12. F1 Team Championship Points
13. F1 Tyre Compound Performance Analysis
14. F1 Weather Impact Analysis
15. F1 Race Results

## Getting Started

### Requirements

- Tableau Desktop (a compatible version that supports the workbook).
- Microsoft Excel or another compatible way to access the source `.xlsx` dataset.
- The Tableau workbook file: `F1 racing dashboard 1.twb`.
- The source dataset: `F1 Racing Project Dataset.xlsx`.

### Open the project

1. Download or clone this repository.
2. Make sure the Excel dataset is available on your computer.
3. Open `F1 racing dashboard 1.twb` in Tableau Desktop.
4. If Tableau reports a missing data source, edit the data connection and select the correct `F1 Racing Project Dataset.xlsx` file.
5. Refresh the data source if required.
6. Open either dashboard from the Tableau workbook's dashboard list.
7. Check filters, chart labels, and visualizations.

## Suggested Repository Structure

```text
F1-Race-Intelligence-Dashboard/
│
├── F1 racing dashboard 1.twb
├── F1 Racing Project Dataset.xlsx
├── README.md
├── report/
│   └── F1_Race_Intelligence_Project_Report.pdf
└── screenshots/
    ├── race-intelligence-dashboard.png
    └── race-performance-dashboard.png
```

The folders and screenshot names above are a suggested organization. Add the report, dataset, and screenshots only if you intend and are permitted to share them.

## Data Validation and Quality Checks

Before presenting or publishing the results, verify:

- All source sheets load correctly.
- Relationships use matching keys and do not create duplicated or missing totals.
- Dates, numeric measures, dimensions, and identifiers have appropriate data types.
- Null values and duplicate records are handled intentionally.
- Aggregations such as `SUM`, `AVG`, `COUNT`, and `COUNTD` are appropriate.
- Filters update the intended charts.
- Dashboard objects are readable, aligned, and not clipped.

## Notes on Analysis

- The workbook includes a dedicated **F1 Pit Stop Analysis** worksheet. Verify its measure and field definitions before interpreting its results.
- Check lap-time and pit-stop measures carefully; average lap time should not be described as pit-stop time.
- Weather comparisons can show differences across weather categories, but do not by themselves prove that weather caused those differences.
- Verify circuit and race aggregations before interpreting totals.
- Add numerical findings only after checking the final workbook, selected season, and active filters.

## Future Improvements

- Add season-over-season comparisons.
- Improve dashboard interactivity with tested filters and parameters.
- Add more detailed driver and team performance trends.
- Publish a Tableau Public version if the workbook and dataset can be shared publicly.
- Add dashboard screenshots and a short project demonstration video.

## Project Files

The main Tableau workbook is provided as a `.twb` file. A `.twb` file stores workbook definitions and references to its data source; it does not package the Excel source data. Keep the source Excel file available and reconnect it when opening the project on another computer.

## Author

**Mayur Patel**  
BCA Student | Medi-Caps University  
Enrollment Number: `EN25CA3020110`

---

*This project is intended for educational purposes and demonstrates data exploration and visualization using Formula 1 racing data.*
