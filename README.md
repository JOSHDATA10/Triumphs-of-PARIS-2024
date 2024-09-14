# Triumphs-of-PARIS-2024
### Exploring the triumphs of Paris 2024 Olympic

This is an explorstory data analysis on the results from Olympics 2024 (Paris 2024). The exploration aims to view trends of medals across various sport activity in different countries. By analyzing this data , we seek to see the number of participants per events and countries and total medal won in each.

### Data Source

The Database used fro this analysis is the 'Olympics_2024.csv", containing detailed information about medals won, medalist , countries and more.

### Tools

- Excel - Data cleaning
- Power BI - Visualization and reports

### Data cleaning
In the data preparation phase, i performed the following tasks:
1. Data loading and inspection
2. Handling missing values.
3. Removed null values and duplicate values
4. Data cleaning and formatting

### Data analysis
I wrote some interesting DAX syntax to calculate columns and metrics
```DAX
Age = DATEDIFF(athletes[birth_date],TODAY(),year)
```
