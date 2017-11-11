# LATEST ASSIGNMENT - 8 
## “SCU-MSIS Students, competent and equipped for and attested by the industry”


## Introduction

SCU’s MSIS program is the top 26th in the whole of the US
List of courses offered at SCU includes business and data analytics, project management, database, visualization, cloud computing and many more.
SCU MSIS graduates employed in the top firms.



## About this visualization 

This visualization is created to support the claim that the SCU-MSIS Students are competent and equipped for and attested by the industry.


## Redesign Goal

The Goal here is to redesign the previously made dashboard to a more comprehensive and perceptive visualization.


### Data Wrangling and Reproducibility

The Data Wrangling is done on Python which can be seen in the jupyter notebook (Lab8.ipynb) uploaded above. 
Used requests to extract data from websites (mentioned in the jupyter notebook). Coming up with a logic to not only extract data but also to correctly format it and download it in terms of columns and rows was difficult. Some of the data about MSIS alumini was dynamic javascript and i attempted to use selenium but failed to extract. Due to this i had to manually create a spreadsheet inputting the data which was a little time consuming. 

## About the previous visualization

![Alt Text](https://github.com/bhargavre/Dashboard_Labs/blob/master/Lab5.PNG)


IT is an amazing visualization that shows 3 different metrics that recruiters and students can see and and make a decision about the MSIS at SCU. 
It has too many colours and is not quite detailed out.


## The Redesigned visualization

![Alt text](https://github.com/bhargavre/Dashboard_Labs/blob/master/Dashboard%209.png)

Tableau link: https://public.tableau.com/shared/M4N72HFRM?:display_count=yes

This visualization is a redesign of the previous visualization. This supports the same claim giving more details about each metric for example ranking which shows comparision between scu and San Jose state university which is present in the same area.

## Warrant

MSIS Ranking
Looking at the rankings especially for MSIS across the US, SCU is ranked among the highest. The ranking is based on the faculty, performance of Students, courses offered and placements after masters. A good ranking indicates that SCU performs well on all these accounts.

Skillset Match
In the fact sheet, we see the minimum and most important set of skills needed by the industry in fields of information systems. These skill sets are offered in the MSIS program at SCU which means the students who finish the program are better equipped to match the industry needs.

Hired by top companies
The companies listed in this chart are those top companies in which SCU MSIS graduates have been absorbed in. This clearly shows that the MSIS students are sort after by the industry. 
Sources of the data include independent and unbiased websites like linkedIn and bestmasters.com

## Backing
The courses at MSIS keep getting updated based on the needs of the industry. The courses are not the same as it was a few years back indicating SCU makes sure that that courses offered are relevant. SCU also hosts  job fairs throughout the year to encourage interaction of students and the hiring companies. This is inline with SCU’s commitment to serving industry needs.  

## Qualifiers
SCU-MSIS Students are surely very competent and equipped for the industry. This is  evident by the fact that they have been hired by some of the top firms in the industry.
 
## Rebuttal/Reservations
The dashboard shows that MSIS graduates are hired by the companies but there is no claim that says what skills they are using in the company. 
It does not show if all the students of the MSIS program were able to find jobs. 
It also does not indicate the feedback about the courses. It only says that it matches the industry need, but about the course itself there is no rating or feedback to indicate the quality of the course.
It does not show the different recruiters who come to the university, but shows the kind of students who graduate so recruiters can come to SCU to select students.

## Conclusion

Students who graduate from the MSIS program at SCU are skilled, bright and competent enough to be hired into top firms and work with people who are among the best in the world.



## References
https://www.linkedin.com/school/10458916/

http://higheredublog.com/top-universities-for-ms-in-mis-in-usa/

https://www.scu.edu/business/ms-information-systems/

http://study.com/articles/Top_Ranked_School_for_Information_Technology_-_San_Jose_CA.html

https://www.forbes.com/colleges/santa-clara-university/

https://www.scu.edu/business/undergraduates/community/global-fellows/placements/by-major/







# LATEST ASSIGNMENT - 7 
## “The financial markets do not punish security breaches.”


## Introduction

The 2017 Cost of Data Breach Study shows that $141 is the average cost per lost or stolen records and $3.62 million is the average total cost of data breach. The costs include law suit costs, the payment needed to be made to customers who lost data and also cost to take measures for the breach.
This might lead us to believe that a data breach costs the company a lot of money and has to have a big effect on the share holder's belief of the company.


## About this visualization 

This visualization is created to support the claim that the financial markets do not punish the security breaches.


## Redesign Goal

The Goal here is to redesign the previously made dashboard to a more comprehensive and perceptive visualization.


### Data Wrangling and Reproducibility

The Data Wrangling is done on Python which can be seen in the jupyter notebook (Lab7.ipynb) uploaded above. 
Apart from cleaning the data (life is beautiful which is referenced below) on python by removing columns and ordering font and values (dont in lab 1 and lab 2), Fuzzy Wuzzy and pandas datareader was also used to gather the stok price for the companies from 2004 - 2017.
Python code was written to acquire the necessary stock price data that revolved around the data breach period.

The bar chart "Companies showing different effects on Breaches on Share Price" was formulated by analyzing the stock price trend line over different years for each ticker symbol (company). Recording the change like Increase, Decrease, No Effect in stock price was analysed by looking at the trend line around the year of data breach.


## About the previous visualization

![Alt Text](https://github.com/bhargavre/Dashboard_Labs/blob/master/Dashboard%203.png)

Tableau link: https://public.tableau.com/views/Book1_24462/Dashboard3?:embed=y&:display_count=yes&publish=yes

IT is an amazing visualization that shows overall data records stolen vs the share price without the clutter of the first. The bar graph shows us the percentage and number of companies in each of the categories of how the breach changed their share price. If we ignore the no-data and breaches before IPO then we can see that only in 20% of the companies there was a decrease in share price and for the rest of the companies the share price was either same or it increased. From this graph we can also say that the increase in overall stock is due to the performance of the companies and not due to data breaches.

However, this does not really show the change in stock due to data breaches for companies to completely solidify the claim.


## The Redesigned visualization

![Alt text](https://github.com/bhargavre/Dashboard_Labs/blob/master/Final%20Dashboard.png)

Tableau link: https://public.tableau.com/views/Lab7-Redesign/FinalDashboard?:embed=y&:display_count=yes&publish=yes

This visualization is simply an extension of the previous visualization as there is a addition of companies whose stock price has incurred change around the data breach period. This particular example charts show that 
+ Apple's and Facebook's share price continued to increase despite of data breach.
+ MSpy's share price was stable despite the data breach.
+ Talktalk showed that it was hit badly in terms of stock price during the year of data breach. This does not conclude or refute the claim entirely, as the claim is about a general question which is 'do security breaches really affect stock prices?'. This is one of the very few companies that has showed sudden and drastic decline in the stock prices.

(NOTE: the bar graph is not displayed properly on Github, visit the tableau public link above to see the actual visualization)


## Conclusion

Data breaches is simply not cared about as we can gather from the news.
We can also say that the companies whose share price decreased were really outliers and financial market does not really punish security breaches.


## References
http://d.yimg.com/autoc.finance.yahoo.com/autoc?query={}&region=1&lang=en

https://docs.google.com/spreadsheets/d/1Je-YUdnhjQJO_13r8iTeRxpU2pBKuV6RVRHoYCgiMfg/edit#gid=322165570

http://www.informationisbeautiful.net/visualizations/worlds-biggest-data-breaches-hacks/





## LATEST ASSIGNMENT - 4
Claim - The MSIS graduates from Santa Clara University - Leavey School of Business are best trained and equipped to compete in the industry

Information in jupyter file Lab 4 has the evidence for the claim.



LATEST ASSIGNMENT - 3
“The financial markets do not punish security breaches.”

The 2017 Cost of Data Breach Study shows that $141 is the average cost per lost or stolen records and $3.62 million is the average total cost of data breach. The costs include law suit costs, the payment needed to be made to customers who lost data and also cost to take measures for the breach.  

This might lead us to believe that a data breach costs the company a lot of money and has to have a big effect on the share holder's belief of the company. Let us see if this is the case by observing the share price before and after a data breach.

The first dashboard: https://public.tableau.com/views/LabAssignment3/Dashboard1?:embed=y&:display_count=yes&publish=yes
shows the share price variation during a breach for all the companies. A first glace shows that there is no visible effect of the breaches on share prices. But the graph is too crowded with too much data.

The second dashboard:https://public.tableau.com/views/LabAssignment3/Dashboard2?:embed=y&:display_count=yes
picks up 4 companies which have had their share prices differently affected by data breaches. Apple and Facebook shows a constant increase in their share price irrespective of the breach. TalkTalk on the other had was affected badly while MSPYX didnt show any change at all. From this graph we get a hint as to how the data breach may not affect stock price. So it would be intersting to see how many companies fall in each of these categories.

The third and final dashboard:https://public.tableau.com/views/Book1_24462/Dashboard3?:embed=y&:display_count=yes&publish=yes
shows the overall data records stolen vs the share price without the clutter of the first. The bar graph shows us the percentage and number of companies in each of the categories of how the breach changed their share price. If we ignore the no-data and breaches before IPO then we can see that only in 20% of the companies there was a decrease in share price and for the rest of the companies the share price was either same or it increased. From this graph we can also say that the increase in overall stock is due to the performance of the companies and not due to data breaches. Data breaches is simply not cared about as we can gather from the news.

In conclusion, We can say that the companies whose share price decreased were really outliers and financial market does not really punish security breaches. 



ASSIGNMENT
Lab 2 - “Security breaches are becoming less severe”

Intermediate Version 1: https://public.tableau.com/views/labassignment2/Dashboard2?:embed=y&:display_count=yes&publish=yes
Intermediate Version 2: https://public.tableau.com/views/labassignment2/Dashboard3?:embed=y&:display_count=yes
Intermediate Version 3: https://public.tableau.com/views/labassignment2/Dashboard1?:embed=y&:display_count=yes

Final Version: https://public.tableau.com/views/labassignment2/Sheet4?:embed=y&:display_count=yes&publish=yes

This Final graph, shows the increase in severity of data breaches over the years.  SSN, Email Addresses and Bank account information theft has seemed to increase in 2017, which shows a concern and an immediate action needed to be taken. The reason for this graph is to show that data breach is becoming more severe and specifically which details are being stolen.

Conclusion: The security breaches for certain kinds of data leaks are becoming more severe.




# Dashboard_Labs
MSIS Dashboards, Scorecard

Information is Beautiful - Lab1

Tableau public
https://public.tableau.com/views/dashboard-informationisbeautiful/Dashboard1?:embed=y&:display_count=yes&publish=yes




