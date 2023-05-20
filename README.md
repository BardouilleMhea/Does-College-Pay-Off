# Does-College-Pay-Off-

"The wage gap between young workers with and without bachelor’s degrees has never been larger. On average, recent college graduates earn $52,000 per year, while young workers with high school diplomas but no higher education credential earn only $30,000 per year. The difference in wages between college and high school graduates – often referred to as the college wage premium – has increased since the start of the COVID-19 pandemic. "  (Source: [Geary, 2022](https://www.newamerica.org/education-policy/edcentral/college-pays-off/))

The **college wage premium** is one of the economic benefits that entice many young adults to attend university. However, going to college does not guarantee economic success. 

Thus, many college-bound students face the challenge of selecting a major that improves their odds of financial success. 

This project uses [grad-students.csv](https://github.com/fivethirtyeight/data/blob/master/college-majors/grad-students.csv), a dataset on the job outcomes, basic earnings and labor force information of students who graduated from college between 2010 and 2012 (ages 25+). 

The original data on job outcomes was released by American Community Survey 2010–2012 Public Use Microdata Series, which conducts surveys and aggregates the data.

Each row in the dataset represent a different major in college and contains information on gender diversity.

Headers for grad-students.csv are shown below:
|  Header       | Description  |
| ------------- | ------------- |
| Rank          | Rank by median earnings (**the dataset is ordered by this column**)  |
| Major_code    | Major code, F01DP in ACS PUMS |
| Major         | Major description             |
| Major_category| Category of major from Carnevale et al |
| Total         | Total number of people with major |
| Men           |Male graduates|
| Women         | Female graduates|
| ShareWomen    | Women as share of total|
| Employed     | Number employed (ESR == 1 or 2)|
| Full_time    | Employed 35 hours or more|
| Part_time    | Employed less than 35 hoursl|
| Full_time_year_round    |Employed at least 50 weeks (WKW == 1) and at least 35 hours (WKHP >= 35)|
| Unemployed    |Number unemployed (ESR == 3)|
| Unemployment_rate    | Unemployed / (Unemployed + Employed)|
| Median    | Median earnings of full-time, year-round workers|
| P25th    | 25th percentile of earnings|
| P75th    | 75th percentile of earnings|
| College_jobs    | Number with job requiring a college degree|
| Non_college_jobs    | Number with job not requiring a college degree|
| Low_wage_jobs    | Number in low-wage service jobs|




Programming Lanugage Used: *Python*
