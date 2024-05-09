# MGT4250 Spring 2024 Course Project
Author: Michael Myers, mmyers23@elon.edu
## Project link: https://public.tableau.com/app/profile/michael.myers4550/viz/MGT4250DataVisualizationProject/MedianIncomebyUSRegion
## Project Description
This purpose of this repostitory is to showcase my MGT4250 Data Visualization course project at Elon University. In this project, I wanted to look at the monetary value of attending college in terms of annual income after graduation. In other words, I'm looking at the financial value of college. Of course, there are several considerations for an individual to take when choosing a college to attend, but this project will focus on financial aspects. The questions that I would like to answer are the following:  
### Questions of interest
- How much does location of college impact the earnings of an individual?
- What is the debt to income ratio after graduation?
- How much does level of degree impact earnings after graduation?
- How much does college major impact the earnings of an individual?
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
The data used in these visualizations come from the College Scorecard website which is maintained by the US Department of Education. I used the most recent data set available to create visualizations. In order to access the data, I have uploaded two zip files to this repository, one named Most Recent Cohorts Field of Study and the other named Most Recent Cohorts Institution. Each one of these zip files contain an Excel sheet, so there are two Excel sheets in total. Once you have extracted these two Excel files then you will have downloaded the data needed for the visualizations.
#### The first visual uses data from Most Recent Cohorts Institution. It uses the Stabrr data column which contains a list of all US states and territories in string format. Using the Stabbr column, I created a new column Region which groups individual states and territories by region. It also uses the Mdn Earn Wne 4 yr data column which contains individual incomes earned 4 years after completing college in integer format.
#### The second visual uses data from Most Recent Cohorts Institution. It uses the Grad Debt Mdn data column which contains the total amount of debt for an individual after completing college in float format. It also uses the Mdn Earn Wne 4 yr data column.
#### The third visual uses data from Most Recent Cohorts Field of Study. It uses the Creddesc data column which contains degree levels by description in string format. It also uses the Earn Mdn 4 Yr data column which contains individual incomes earned 4 years after degree completion in integer format.
#### The fourth visual uses data from Most Recent Cohorts Field of Study. It uses the Cipcode data column which contains numerical ids for college majors in string format. For this visual I grouped the Cipcode data into groups according to similar majors and created a new column called Field of Study in string format. It also uses the Earn Mdn 4 Yr data column.
## Interpreting Visualization
![image](https://github.com/mimyers-95/mgt4250spring2024/assets/79224403/96512f57-ac83-4f5a-8aca-6611cad59c9c)

For the first visualization, I wanted to look at the question of how location of college affects individual income after graduation. I looked at the median yearly income after four years of individuals who graduated and grouped these incomes by region. The visual tells us that graduates in New England tend to earn the highest median income at around 46500/year, while graudates in US territories like Puerto Rico and Virgin Islands tend to have the lowest median incomes at around 21500/year, which shows about a 25000 dollar difference between regions. We also see that the Mountain, Southeast, and Southwest regions all have simliar incomes ranging from 35500-37000/year. This indicates that where you graduate from college has a great impact on your future earnings.
  
![image](https://github.com/mimyers-95/mgt4250spring2024/assets/79224403/04e5d55c-3824-4ba3-b34e-590b8a4be112)

For the second visualization, I wanted to look at the question of debt to income after graduation. We can see that even though graduates from US territories have the lowest median yearly income, they also tend to have the lowest debt after graduation being almost 10000 dollars lower than graduates from New England who tend to have the highest debt. However, in terms of debt to income ratios, graduates from US Territories have the highest at 44%, while graduates from the Southwest have the lowest at around 29%. It's also interesting to note that regions with higher median incomes tend to have higher debts as well. I also added a linear trend line and it has a p-value of <0.05. This shows us that the correlation between debt after graduation and yearly income after graduation is significant.

![image](https://github.com/mimyers-95/mgt4250spring2024/assets/79224403/ad84854d-0563-4bcb-b79f-fa87b9b4bc53)

For the third visualization, I look at the question of degree level and how much it impacts yearly earnings. The visual clearly shows that higher degree levels correlate to higher income with about a 55000/year difference between doctoral degrees and high school diplomas. Even between a high school diploma and bachelor's degree the difference is quite significant at about a 20000 dollar increase.

![image](https://github.com/mimyers-95/mgt4250spring2024/assets/79224403/6859a2d8-ba24-4b02-b729-bbdf946a96d5)

For the fourth visualization, I look at answering the question of how much does college major impact yearly earnings. This visual shows that medical doctors are the top earning field of study at about 180000/year. At the lower end, the visual shows Cosmetology and Culinary at around 20000/year. We see that the top earning fields with median earnings above 60000/year tend to have a focus on science, mathematics, and technology. Clearly, there are vast differences between potential earnings when it comes to college majors.
## Discussion & Summary
### Article link: https://cew.georgetown.edu/wp-content/uploads/cew-college_payoff_2021-fr.pdf
To summarize, the article states that lifetime earnings tend to increase for individuals as education level increases, but it is not always the case. For example, it says 28% of associate's degree holders earn more than those holding bachelor's degrees. The article also talks about the importance of field of study and shows that earnings can vary greatly between fields. For example, bachelor's degree in architecture, engineering, and mathematics tend to have the most lifetime earnings over other fields of study at a bachelor's level. The article also mentions that lifetime earnings varies across states even when adjusting for cost of living.
### Chat GPT Responses:
- How much does location of college impact the earnings of an individual?

The location of a college can have a notable impact on the earnings of an individual after graduation. Several factors contribute to this influence:

1. **Cost of Living**: Colleges situated in regions with higher costs of living may result in higher salary expectations to maintain a comparable standard of living. Conversely, colleges in areas with lower costs of living may correlate with lower salary expectations.

2. **Job Market**: The local job market and industry presence play a significant role. Graduates from colleges located in regions with robust job markets and strong demand for their skills may have better access to employment opportunities and potentially higher salaries.

3. **Networking Opportunities**: Larger cities or regions often offer more extensive networking opportunities with professionals and alumni, potentially leading to better job prospects and higher salaries after graduation.

4. **Industry Concentrations**: Certain locations are known for concentrations in specific industries or sectors. Attending college in proximity to these industry hubs may provide graduates with better access to internships, job opportunities, and higher salaries within those fields.

5. **Local Economy**: The overall economic health and growth rate of the region can influence job availability and salary levels. Strong, growing economies generally offer better job prospects and higher earning potential for graduates.

6. **Regional Wage Disparities**: Wages can vary significantly between different regions and cities due to factors such as local economic conditions, cost of living, and industry specialization. Graduates may find that their earning potential varies based on where they choose to work after graduation.

While the location of a college can impact earnings after graduation, it's essential to consider other factors such as individual qualifications, experience, and career choices. Additionally, remote work opportunities and the globalization of certain industries may mitigate some of the location-based disparities in earning potential.

- What is the median debt to income ratio after graduation?

As of my last update in January 2022, I don't have access to real-time data, so I can't provide the most current median debt-to-income ratio after graduation. However, I can provide some general insights.

The median debt-to-income ratio after graduation can vary based on a variety of factors, including the type of institution attended, the amount of student loan debt accumulated, the individual's chosen field of study, and their post-graduation income level.

Several studies and reports have indicated that the median debt-to-income ratio for recent graduates can range anywhere from around 15% to 30% or higher, depending on these factors. However, these figures can fluctuate over time and may differ based on specific demographic or socioeconomic factors.

It's important to note that the median debt-to-income ratio is just one metric and may not fully capture the financial circumstances of all graduates. Additionally, individual experiences with student loan debt and income levels can vary widely.

- How much does level of degree impact earnings after graduation?

The level of degree obtained can significantly impact earnings after graduation. Generally, individuals with higher levels of education tend to earn higher salaries on average. Here's how different levels of degrees can impact earnings:

Associate's Degree: Individuals with an associate's degree typically earn more than those with just a high school diploma. However, earnings may be lower compared to those with higher-level degrees. Associate's degrees often lead to careers in fields such as healthcare, technology, and skilled trades.

Bachelor's Degree: A bachelor's degree is often considered the entry-level requirement for many professional careers. On average, individuals with a bachelor's degree tend to earn significantly more over their lifetimes compared to those with lower levels of education. The specific field of study can also impact earning potential.

Master's Degree: Holding a master's degree can lead to higher earning potential compared to a bachelor's degree alone. Many specialized and managerial positions require or prefer candidates with a master's degree. Fields such as business, healthcare, education, and engineering often reward individuals with master's degrees with higher salaries.

Professional Degree (e.g., MD, JD, PharmD): Professional degrees are typically required for specific professions such as medicine, law, pharmacy, and others. Individuals who obtain professional degrees often command significantly higher salaries due to the specialized nature of their work and the extensive education and training required.

Doctoral Degree (e.g., PhD): Doctoral degrees are the highest level of academic achievement and are typically required for careers in academia, research, and certain specialized fields. Individuals with doctoral degrees often earn higher salaries, particularly in fields where advanced expertise and research skills are valued.

It's important to note that while higher levels of education generally correlate with higher earnings, other factors such as field of study, industry demand, geographic location, and individual experience also play significant roles in determining salary levels after graduation.
