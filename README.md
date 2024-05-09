# MGT4250 Spring 2024 Course Project
Author: Michael Myers, mmyers23@elon.edu
## Project link: https://public.tableau.com/app/profile/michael.myers4550/viz/MGT4250DataVisualizationProject/MedianIncomebyUSRegion
## Project Description
This purpose of this repostitory is to showcase my MGT4250 Data Visualization course project at Elon University. In this project, I wanted to look at the monetary value of attending college in terms of annual income after graduation. In other words, I'm looking at the financial value of college. Of course, there are several considerations for an individual to take when choosing a college to attend, but this project will focus on financial aspects. The questions that I would like to answer are the following:  
### Questions of interest
- How much does location of college impact the earnings of an individual?
- How much does level of degree impact earnings after graduation?
- How much does college major impact the earnings of an individual?
- What is the debt to income ratio after graduation?
### Importance
- This is *especially* **important** because
 1.  The upfront cost of college is often a huge financial investment and can take up to many years for a student to
pay it off before it is considered a net positive financially. 
 2.  The price of this investment can vary greatly depending on college tuition in different regions of the country. Not to mention, there is a large disparity of income between college majors.
### References:
#### https://www.forbes.com/advisor/education/student-resources/is-a-college-degree-worth-it/
#### https://www.cnbc.com/2021/11/02/the-gap-in-college-costs-and-earnings-for-young-workers-since-1980.html
#### https://www.chicagofed.org/publications/chicago-fed-insights/2024/is-college-a-worthwhile-investment
## Data Description
The data used in these visualizations come from the College Scorecard website which is maintained by the US Department of Education. I used the most recent data set available in to create visualizations. In order to access the data, I have uploaded two zip files to this repository, one named Most Recent Cohorts Field of Study and the other named Most Recent Cohorts Institution. Each one of these zip files contain an Excel sheet, so there are two Excel sheets in total. Once you have extracted these two Excel files then you will have downloaded the data needed for the visualizations.
#### The first visual uses data from Most Recent Cohorts Institution. It uses the Stabrr data column which contains a list of all US states and territories in string format. Using the Stabbr column, I created a new column Region which groups individual states and territories by region. It also uses the Mdn Earn Wne 4 yr data column which contains individual incomes earned 4 years after completing college in integer format.
#### The second visual uses data from Most Recent Cohorts Field of Study. It uses the Creddesc data column which contains degree levels by description in string format. It also uses the Earn Mdn 4 Yr data column which contains individual incomes earned 4 years after degree completion in integer format.
#### The third visual uses data from Most Recent Cohorts Field of Study. It uses the Cipcode data column which contains numerical ids for college majors in string format. For this visual I grouped the Cipcode data into groups according to similar majors and created a new column called Field of Study in string format. It also uses the Earn Mdn 4 Yr data column.
#### The fourth visual uses data from Most Recent Cohorts Institution. It uses the Grad Debt Mdn data column which contains the total amount of debt for an individual after completing college in float format. It also uses the Mdn Earn Wne 4 yr data column.
## Interpreting Visualization
![image](https://github.com/mimyers-95/mgt4250spring2024/assets/79224403/96512f57-ac83-4f5a-8aca-6611cad59c9c)

For the first visualization, I wanted to look at the question of how location of college affects individual income after graduation. I looked at the median yearly income after four years of individuals who graduated and grouped these incomes by region. The visual tells us that graduates in New England tend to earn the highest median income at around 46500/year, while graudates in US territories like Puerto Rico and Virgin Islands tend to have the lowest median incomes at around 21500/year, which shows about a 25000 dollar difference between regions. We also see that the Mountain, Southeast, and Southwest regions all have simliar incomes ranging from 35500-37000/year. This indicates that where you graduate from college has a great impact on your future earnings.
![image](https://github.com/mimyers-95/mgt4250spring2024/assets/79224403/04e5d55c-3824-4ba3-b34e-590b8a4be112)

For the second visualization, I wanted to look at the question of debt to income after graduation. We can see that even though graduates from US territories have the lowest median yearly income, they also tend to have the lowest debt after graduation being almost 10000 dollars lower than graduates in New England who tend to have the highest debt. It's also interesting to note that regions with higher median incomes tend to have higher debts as well. I also added a linear trend line and it has a p-value of <0.05. This shows us that the correlation between debt after graduation and yearly income after graduation is significant.
![image](https://github.com/mimyers-95/mgt4250spring2024/assets/79224403/ad84854d-0563-4bcb-b79f-fa87b9b4bc53)

For the third visualization, I look at the question of degree level and how much it impacts yearly earnings. The visual clearly shows that higher degree levels correlate to higher income with about a 55000/year difference between doctoral degrees and high school diplomas. Even between a high school diploma and bachelor's degree the difference is quite significant at about a 20000 dollar increase.

## Discussion & Summary
