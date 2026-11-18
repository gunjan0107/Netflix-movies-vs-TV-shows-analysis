# Netflix Country-Wise Content Analysis Dashboard

## Project Overview
This project explores the country information in the Netflix titles dataset and presents country-wise content patterns using Microsoft Excel. The aim is to make geographic distribution easier to compare through summaries and charts.

## Objective
- Prepare the `country` field for analysis.
- Summarize title counts by country.
- Compare country-level contributions to the catalogue.
- Present the results in an easy-to-read Excel dashboard.

## Dataset
The supplied dataset contains **8,790 records** and includes a `country` field alongside title, content type, release year, rating, duration, and genre/category information.

A title may list more than one country. If splitting multi-country entries, document the method and avoid counting one title as a unique title for every country without explaining that approach.

## Tools
- Microsoft Excel
- PivotTables and PivotCharts, if used in the workbook
- CSV dataset

## Workflow
1. Import the dataset into Excel and inspect the `country` field.
2. Identify blank, unknown, or multi-country entries.
3. Decide how multi-country titles will be counted and document that rule.
4. Build a country-level summary using the method used in your workbook.
5. Create charts to compare the leading countries.
6. Add dashboard labels, units, and a short findings section.
7. Validate chart totals against the underlying summary table.

## Questions Explored
- Which countries have the largest number of listed titles?
- How does the catalogue vary geographically?
- Are Movies and TV Shows distributed differently across countries?
- How do missing or multi-country values affect the interpretation?

## Recommended Visuals
Choose only the visuals actually present in your workbook:
- Bar chart of top countries by title count.
- Comparison of Movies and TV Shows by country.
- KPI cards for total records and distinct countries, if calculated.
- A note explaining how multi-country titles are handled.

## Repository Contents
Suggested files:
- `Dataset.csv` — source dataset, if redistribution is permitted.
- `Netflix_Country_Analysis_Dashboard.xlsx` — Excel workbook.
- `screenshots/` — dashboard screenshots.
- `README.md` — project documentation.

Update filenames to match your uploaded files.

## Key Findings
Add 3–5 findings from your actual dashboard here. Include the country ranking and counts only after checking the workbook. Do not copy unverified numbers into the README.

## Limitations
Country values may contain multiple countries per title or missing/unknown entries. The ranking depends on how these records are handled. The dataset is a snapshot, not live Netflix availability data.

## Author
Gunjan Sahni
