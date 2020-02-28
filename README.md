# Regressions-and-Correlations-with-Baltimore-Incarceration-Rates

**Data Sources:** Opportunity Atlas Data for Baltimore City based on four indicators: incarceration rates, teen birth rates, Employment rate and household income 

**Business Question:** I am a data analyst for mayor of the city of Baltimore, Bernard Young, and the city council is about to begin voting on the budget. The council’s main goal is to reduce incarceration rates, but the budget is limited and can only allocate funds to one initiative. My job as a data analyst for the city is to answer the following business question: Which factors between household income, employment rates and teenage birth rates and have the highest impact on incarceration rates? Using this information, we can write up a convincing proposal to the city council. 

Based on the business related question the following **data related questions** are pertinent:
1. What is the relationship between incarceration rates and household income, teenage birth rates and employment rates? What is the curve of this relationship?
2. Which x values are most significant amongst the three for determining incarceration rates?
3. Is there a strong correlation between these values? Is it positive or negative?
4. What are the chances that these independent variables are at the cause of the dependent variable? What do our p values and f significance tell us about this?

Based on the the answer to the data related questions, the city council will decide between:
- Raising minimum wage to raise household income
- Funding a comprehensive job creation program to increase employment rates
- Funding a planned  parenthood initiative to tackle teenage birth rates

**Data Related Findings:**
1. Based on the first regression, 72.5% of variation in incarceration can be explained by household income, employment rates and teen birthrates. 
2. Moreover, the low significance F signifies that at least one of these values matter to determining incarceration rates
3. That being stated, when looking at the significance of each variable in determining incarceration rates, household income and employment rates remain relatively insignificant. The only significant variable is teenage birth rates.
4. Based on this fact a second regression in which the only independent variable was teen birth rates, showed that 72% incarceration rates could be explained by teen birthrates and the p value and f significance showed significance in determining incarceration rates.
5. From there, data on correlations showed negative correlation and very slight negative correlation between household income and employment rates, respectively, and incarceration rates.
6. Teenage birthrates showed a positive correlation meaning that as teenage birth rates rose, so did incarceration rates.
7. An interesting relationship, aside from incarceration rates, is between teenage birth rates and household income, which are very negatively correlated indicating an important relationship.

**Conclusions:**
Based on our data, it is clear that in evaluating sociological factors, establishing clear correlation and relationships is difficult. It is usually not a single isolated variable, that will have a direct effect on another social variable. Still, the strongest relationship to incarceration, based on our data, seems to be between teenage birth rates and incarceration rates. Thus my suggestion to the city council is the following:
Choose to spend the allocated funds towards a widespread planned parenthood program. This based on our data, should decrease teen birth rates, and decrease incarceration rates in the long run.

**Excel Step by Step Walkthrough**
1. I used V-Lookup to match the tract numbers of different location data sets, to the tract numbers of location data on inCarceration rates
2. I used the Analysis Tool-Pak add-in and under the “Data” tab, selected data analysis. I selected incarceration rates as my dependent variable, and the other three variables as my independent variables, and ran the regression.
3. I used similar steps for the second regression, but with teen births as my only independent variable
4. On tab “Correlation, ” I ran the correlation function between my variables. I did this also between teen birth rates and incarceration rates, and made a graph.
5. I finally made a line graph to show the different peaks based on each region. I used a secondary axis to adequately map household income. 

**Excel Files**
https://github.com/mdia4/Regressions-and-Correlations-with-Baltimore-Incarceration-Rates/blob/master/Mini%20Project%202.xlsx
https://github.com/mdia4/Regressions-and-Correlations-with-Baltimore-Incarceration-Rates/blob/master/Baltimore%20Employment%20rates.xls
https://github.com/mdia4/Regressions-and-Correlations-with-Baltimore-Incarceration-Rates/blob/master/Household%20income%20baltimore.xls
https://github.com/mdia4/Regressions-and-Correlations-with-Baltimore-Incarceration-Rates/blob/master/Baltimore%20Incarceration%20project%202.xls
https://github.com/mdia4/Regressions-and-Correlations-with-Baltimore-Incarceration-Rates/blob/master/Teengage%20Birthrates%20Baltimore.xls
