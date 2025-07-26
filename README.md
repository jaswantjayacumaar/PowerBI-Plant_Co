# Plant Co. Performance Dashboard

This repository contains the **Plant Co. Performance Dashboard**, a Power BI project designed to analyze sales performance, gross profit, and country-specific trends across multiple years. Built using the `Plant_DTS.xls` dataset, the dashboard offers interactive visualizations to support data-driven decision-making for stakeholders.

## Overview

The dashboard leverages Power BI's robust analytics to transform complex datasets into intuitive visual representations. It compares year-to-date (YTD) versus prior year-to-date (PYTD) metrics, segments account profitability, and provides insights into financial performance. Key features include a dropdown menu for year selection and drill-down capabilities for deeper analysis.

## Features
- **KPI Cards**: Display YTD Gross Profit, YTD vs PYTD, PYTD Sales, and GP% with color-coded indicators.
- **Treemap**: Highlights top 10 underperforming countries by sales performance.
- **Waterfall Chart**: Visualizes monthly sales changes with drill-down mode for detailed exploration.
- **Clustered Column Chart**: Compares YTD and PYTD by month and product type.
- **Scatter Plot**: Segments account profitability with a 40% GP% threshold.
- **Slicer**: Enables year selection and toggles between quantity and sales metrics.

## Dataset
- [Plant_DTS.xls](Plant_DTS.xls)

## Usage
- Launch the dashboard in Power BI Desktop to explore interactive visualizations.
- Use the slicer to select a year and toggle between sales and quantity metrics.
- Utilize drill-through and drill-down features to analyze country or product-level data.
- Export insights or screenshots for reporting purposes.

## Tools and Techniques
- **Power BI Desktop**: For modeling and dashboard design.
- **Power Query**: For data cleaning and transformation.
- **DAX**: For time-intelligent calculations.

## Repository Structure
- `/Report`: Contains JSON files for report visuals.
- `/SemanticModel`: Contains TMDL files for the data model.
- `/screenshots`: Images of the dashboard.

### File Descriptions
- **.pbip file**: The Power BI project file, which serves as a solution file for managing the dashboard's source code, data model, and report definitions in a collaborative environment.
- **.pbix file**: The Power BI report file, a standalone file containing the complete dashboard with data, visuals, and interactivity for direct use in Power BI Desktop.
- **PDF containing the report**: A compiled document summarizing the dashboard's design, insights, and usage instructions, generated from the project documentation.

## Screenshots
- **Figure 1: Initial Dashboard View** - Displays the main layout with KPI cards, treemap, and charts.
  ![Figure 1](https://github.com/jaswantjayacumaar/PowerBI-Plant_Co/blob/main/Screenshots/Drill%20Down%20Mode.jpg)
- **Figure 2: Drill-Down Mode View** - Shows detailed data exploration for specific metrics.
  ![Figure 2](https://github.com/jaswantjayacumaar/PowerBI-Plant_Co/blob/main/Screenshots/Drill%20Down%20Mode.jpg)
