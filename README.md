# Actual vs. Budget Excel Dashboard
<img width="1475" height="494" alt="Screenshot 2026-09-18 124620" src="https://github.com/user-attachments/assets/54a94778-278e-4cbc-8ac6-75b76cc8a9a7" />
<img width="1851" height="487" alt="Screenshot 2026-09-14 233338" src="https://github.com/user-attachments/assets/3db06ff8-ce39-4e21-a88a-9ef831770030" />


## Introduction
This dashboard was created to show how I built a dynamic actuals vs budget dashboard from scratch for a hypothetical company's internal budget.

Two dashboard tabs were created in the Excel file to showcase the Excel skills used and the different charts. In the 'Dashboard' tab, variance analysis was used to determine how much of a difference there is between
the budget and actual amounts.

### Dashboard File
My Excel dashboard is in [Actual vs Budget Dashboard 2025 (version 2).xlsx](https://github.com/user-attachments/files/32199297/Actual.vs.Budget.Dashboard.2025.version.2.xlsx)

### Excel Skills Used
- :bar_chart: Charts:
- :heavy_division_sign: Formulas and Functions (e.g. SUMIFS)
- :negative_squared_cross_mark: Data Validation
- Slicers

### Data Jobs Dataset
The financial dataset used for this project was adapted from https://www.kaggle.com/datasets/kennathalexanderroy/budget-vs-actual-financial-dataset on Kaggle. According to the original source, the dataset simulates
realistic corporate financial transactions categorized by department, expense category, and region, covering the period from 2021 to 2023.

The original dataset primarily contained expense-related data. To make the dataset more representative of a real-world corporate financial environment, it was modified using AI to incorporate income data, specifically
Product Revenue and Service Revenue. The date range was also adjusted to focus exclusively on 2023. 

## Dashboard Build
:bar_chart: Charts:
### Income and expense - Clustered Column Chart
<img width="770" height="467" alt="Screenshot 2026-09-19 201650" src="https://github.com/user-attachments/assets/b64f2b1d-ebbb-4098-a1c9-04b397304e67" />

- Excel Features: Utilized an Excel clustered column PivotChart to display monthly performance.
- Design Choice: Paired contrasting shades of blue (dark blue for Actual, light blue for Budget) to create clear, vertical visual comparisons.
- Visual Enhancement: Added direct data labels on top of each column for clarity.
- Insights Gained: With the interactive Month Slicer placed on the side, stakeholders can easily customize the timeframe —viewing individual months or multi-month trends—to identify where actual expenses overshot the budget.


### Income and expense per category - Pie Chart
<img width="784" height="355" alt="Screenshot 2026-09-28 170601" src="https://github.com/user-attachments/assets/981a3bc9-69ef-44db-aec1-c12e9fa3eca6" />

- Excel Features: Designed two separate, synchronized pie PivotCharts to analyze categorical distributions side-by-side.
- Design Choice: Mapped an identical 8-color palette across both charts to ensure a consistent visual link when comparing specific categories from chart to chart.
- Data Representation: Plotted percentage shares for individual revenue streams and costs—including Infrastructure, Marketing, Product Revenue, Salaries, Service Revenue, Training, Travel, and Utilities.
- Visual Enhancement: Integrates interactive left-hand Slicers (filtering by 'Type' and 'Region') allowing users to instantly filter all visualizations with a single click.
  - Insights Gained: Pinpoints shift in operational weights, such as Infrastructure growing from a budgeted 6.08% to an actual 7.06% 
