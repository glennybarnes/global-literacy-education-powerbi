# Global Literacy & Education Trends (Power BI)

A Power BI dashboard project analyzing global literacy rates and educational statistics to identify trends, disparities, and data-driven policy recommendations.

## Project Objective

Literacy rates are a critical indicator of a country’s educational level and future prosperity. This project explores:

- Global literacy trends
- Gender disparities in education
- The impact of GDP and government spending on educational outcomes

We used interactive Power BI visualizations and DAX measures to bring these insights to life and support global efforts toward universal education.

## Research Questions

- What are the literacy rates across different countries?
- Does government spending on education affect a country’s average years of schooling?
- Does Gross Domestic Product (GDP) affect literacy rates?
- Are there significant differences in literacy rates between females and males?

## Datasets Used

1. **Global Education Statistics**  
   Contains literacy rates, average schooling years, test scores, education quality, and government expenditure by country and year.

2. **Global Demographics**  
   Includes fertility rates, population data, life expectancy, WHO regions, and GDP figures.

3. **UNESCO Literacy Rates Dataset**  
   Provides literacy rates segmented by country, gender, age group, and year.

## Data Cleaning

- Filtered records from 1990 onward to maintain consistency and relevance.
- Preserved original values to maintain data integrity and avoid bias from imputation.

## Data Analysis and DAX Measures

A new DAX column was created to analyze gender disparities:
**Gender Gap (%)** = [Avg Male Literacy] - [Avg Female Literacy]  
This measure calculates the difference in youth literacy rates between males and females across countries.

## Key Insights

### Global Literacy Rates

- Average global literacy rate is 85.4%.
- Top-performing countries include Azerbaijan, Ukraine, and Uzbekistan with rates above 99%.
- Lowest-performing countries include Chad, Burkina Faso, and Niger with rates below 36%.
- Europe has the highest regional average (98.7%), while Africa has the lowest (65.83%).

### Government Spending vs. Years of Schooling

- No strong correlation was found between education spending and years of schooling.
- Countries like Vanuatu and Lesotho spend more but don’t always achieve higher schooling years.
- Nations like Vietnam and Thailand show strong outcomes despite lower education budgets.
- Outliers such as Singapore and Hong Kong demonstrate high spending and high results.

### GDP vs. Literacy

- A negative correlation was observed between GDP and literacy rates.
- High GDP doesn’t always mean high literacy.
- Qatar, for example, contributed significantly to GDP in 2011 but didn't show proportional literacy gains.

### Gender Disparities

- Average male literacy rate is 91.19%, while female literacy rate is 87.86%.
- Countries like Afghanistan, Chad, and Mozambique show large gender gaps (20%+).
- More promising trends were seen in youth literacy rates, with many countries nearing parity for boys and girls.
- However, major gaps persist in countries like South Sudan and Somalia, where female literacy remains significantly lower.

## Recommendations

- Promote targeted campaigns to support girls' education in countries with wide gender gaps.
- Invest in educational infrastructure, especially in underperforming African regions.
- Develop policies to increase average years of schooling and keep children enrolled.
- Raise community awareness to challenge cultural norms restricting girls' education.
- Encourage international support and funding for countries with the lowest literacy rates.
- Continuously monitor and analyze literacy data to inform future interventions.

## Tools and Technologies

- Power BI
- DAX
- Excel
- Data sources from UNESCO, World Bank, and WHO

## Dashboard Preview

<img width="1541" height="866" alt="Screenshot 2025-08-06 at 3 25 25 PM" src="https://github.com/user-attachments/assets/948c49a4-de94-4eb0-a33d-584381a70036" />
<img width="1541" height="866" alt="Screenshot 2025-08-06 at 3 25 55 PM" src="https://github.com/user-attachments/assets/8cb79680-e60d-446b-a0e5-c21836d5b189" />


