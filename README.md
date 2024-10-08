# Triumphs-of-PARIS-2024
## Table of content
- [Project Overview](project-overview)
- [Data Source](data-source)
- [Tools](tools)
- [Data cleaning](data-cleaning)
- [Data analysis](data-analysis)
- [Results/Findings](results/findings)
- [Conclusion](conclusion)

## Project Overview
### Exploring the triumphs of Paris 2024 Olympic

This is an explorstory data analysis on the results from Olympics 2024 (Paris 2024). The exploration aims to view trends of medals across various sport activity in different countries. By analyzing this data , we seek to see the number of participants per events and countries and total medal won in each.

![Dashboard](oly 3.PNG)

![oly 3](https://github.com/user-attachments/assets/525f6171-b7c9-4d6f-b2d0-a150cf80ec69)

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
AGE 2 = DATEDIFF(medallists[birth_date],TODAY(),YEAR)
RANK = RANKX(medals_total, medals_total[Points total])
Points total = medals_total[Gold total] + medals_total[Silver total]  + medals_total[Bronze total]
```

### Results/Findings
1. USA had the highest medal 111
2. USA had the highest medal points, 216. USA was the winner of the 2024 Paris Olympics.
3. China had the second highest medal points, 176.
4. Athletics and Swimming had the highest number of medals 112 and 105 respectively.
5. The United States of America , had the highest number of athletes for the 2024 Olympics, with over 600 athletes. USA also participated in 47 disciplines , of 49. This could account for the high number of medals won by USA.


### Conclusion
In the grand arena of Paris 2024, the numbers tell a story of determination, excellence, and unmatched 
athletic prowess. 
The USA's dominance with 111 medals and a remarkable 216 points underscores their global 
sportsmanship. Zhang Yufei's six-medal feat and Marchand Leon's golden triumphs reflect the spirit of 
individual brilliance that the Olympics celebrate.
This exploration of Paris 2024 not only captures the triumphs of nations and athletes but also highlights 
the essence of the Olympic spirit—where every medal is a testament to hard work, resilience, and the pursuit of greatness.
