# Power BI Dashboard: Healthcare Waitlist Analysis

## Overview
This repository contains a Power BI dashboard analyzing healthcare waitlist data for inpatient, outpatient, and day case services from 2018 to 2021. The dashboard highlights key trends, specialty-wise insights, and demographic patterns to address waitlist management challenges in the healthcare system.

## Problem Statement
Healthcare systems face increasing challenges in managing patient waitlists due to rising volumes, age-based disparities, and specialty-specific bottlenecks. Ensuring timely access to care while maintaining efficiency requires actionable insights from detailed data analysis.

This project focuses on:

- Analyzing monthly trends in waitlist volumes across inpatient, outpatient, and day case categories.
- Using tooltip drill-downs for in-depth insights into demographics and specialties.
- Identifying key performance indicators (KPIs) for targeted improvements.

## Solution
The Power BI dashboard provides:

1. **Monthly Trend Analysis:**
   - A line chart visualizing waitlist trends across case types.
   - Tooltip drill-downs for specialty and demographic breakdowns.

2. **Key Indicators:**
   - Case type splits, average waitlist sizes, and specialty-wise comparisons.
   - Time band distributions to highlight delays and disparities.

3. **Specialty Insights:**
   - Identification of top specialties contributing to prolonged waitlists.

4. **Interactive Features:**
   - Filters for case type, age profile, specialties, and time bands.
   - Aggregated comparisons across years to evaluate performance.

## Data Sources
The dashboard utilizes the following datasets:

- **Inpatient Waitlist Data (2018-2021):** Includes patient demographics, specialties, and time band details.
- **Outpatient Waitlist Data (2018-2021):** Similar details for outpatient services.
- **Mapping_Specialty.csv:** Maps specialties to broader groups.

## Files in the Repository
- `New Project.pbix`: Power BI dashboard file.
- `Hospital Waitlist Dashboard.pdf`: Reference visualization of the dashboard.
- Data files:
  - `IN_WL_2018.csv`, `IN_WL_2019.csv`, `IN_WL_2020.csv`, `IN_WL_2021.csv`
  - `Op_WL_2018.csv`, `Op_WL_2019.csv`, `Op_WL_2020.csv`, `Op_WL_2021.csv`
  - `Mapping_Specialty.csv`

## Usage
1. Clone this repository:
   ```bash
   git clone https://github.com/manikanta1609.git
   ```
2. Open `Hospital Waitlist Dashboard.pbix` in Power BI Desktop.
3. Interact with the dashboard using filters and drill-downs.

## Contribution
Contributions are welcome! You can:
- Suggest improvements to the dashboard.
- Add datasets or additional insights.
- Report issues or bugs.

## License
This project is licensed under the MIT License. See the `LICENSE` file for details.

## Contact
For questions or feedback, contact [Your Name] at [Your Email].
