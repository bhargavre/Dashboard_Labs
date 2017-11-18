## Introduction

'He uses statistics as a drunken man uses lamp posts – for support rather than for illumination'
 - Andrew Lang

The same thing could be said of data. Data is extremely powerful and unfortunately, by manipulation, it can be used to support what we already believe or want to believe. Instead data should be used as a powerful source of knowledge and let it speak. The dashboards we design needs to do latter.


## My views on this visualization

Consider the following data set

Data Set 1

| Category | Gaming Device | Usage Rate |
| --- | --- | --- |
| Adults | Desktop or Laptop Computer	| 0.73 |
| Adults | Game Console | 0.53 |
| Adults | Mobile Device | 0.35 |
| Adults	| Portable Gaming Device	| 0.35 |
| Non-Parents |	Desktop or Laptop Computer |	0.35 |
| Non-Parents	| Game Console | 0.22 |
| Non-Parents	| Mobile Device	| 0.16 |
| Non-Parents	| Portable Gaming Device	| 0.1 |
| Parents	| Desktop or Laptop Computer	| 0.45 |
| Parents	| Game Console | 0.41 |
| Parents | Mobile Device	| 0.25 |
| Parents	| Portable Gaming Device	| 0.21 |
| Teens | Desktop or Laptop Computer	| 0.76 |
| Teens | Game Console	| 0.89 |
| Teens | Mobile Device| 0.5 |
| Teens	| Portable Gaming Device	| 0.62 |

The infographic that was created using this data set claimed that 53% of adults are gamers. This claim can be miss-constructed from the above data by filtering on Desktop usage and Adults, like we show below.

(Actual image here)
Link Here (makeover monday)
 
Data Set 1 only gives information about what kind of devices each type of gamers use. For example it only says that of all the adult gamers, 53% of them use Desktop or Laptops for gaming. There is no data about the total number of gamers or the proportion of adult vs teens. From this data set the only information that can be gleaned is the following:
 
(Image of 73% adults use desktop and 89% use game console) 
 
The claim that 53% of adults from this data is a clear miss representation of data. [as was done in https://www.forbes.com/sites/kevinanderton/2015/12/31/adults-vs-teens-video-game-edition-infographic/#7f55d43041b0]
One cannot say if this is true or not based on the data available.

In order to check if this claim has any credibility, one needs to get more data. 

+	What percent of US population are gamers?
+	What percent of US population are adults?
+	What percent of gamers in US are adults?


## Reason for Deception



## Data Wrangling

None of the data gathered needed any cleaning on Jupyter notebook. As mentioned above the original data was not enough to validate the credibility. To check if the claim is credible more data was gathered on population in USA and number of adult gamers from references mentioned below. The data from these references were manually extracted to excel as extracting in python was a challenge due to time constraints.
Additionally a math calculation was done to find out the actual number of Adult gamers in the USA which is given under the Visualization Process section. 

## Visualization Process

Using the original data, the reproducibility of the dashboard supporting the claim was attempted. But as mentioned earlier the claim was mis-constructed. 

The visualization below shows what the data actually refers to.
(process 1 image)

As mentioned previously, in order to check if this claim has any credibility, one needs to get more data. 

The information was found at 

https://www.polygon.com/2015/4/14/8415611/gaming-stats-2015

https://www.census.gov/prod/cen2010/briefs/c2010br-03.pdf

https://www.statista.com/statistics/189582/age-of-us-video-game-players-since-2010/

Using data gathered from the above we have the following information:

+	42% percent of US population are gamers.
+	74.3% percent of US population are adults.
+	71% percent of gamers in US are adults.

Using the mathematical calculation below, a manual excel sheet was created with new values

Let us say the population of the US is P

+	42% percent of US population are gamers = 0.42P are gamers

+74.3% percent of US population are adults = 0.743P are adults

+71% percent of gamers in US are adults = 0.71*0.42P are adult gamers

Percentage (%) of Adults who are gamers is given by 

(Adult gamers/Adults)*100

= ((0.71*.42P)/0.743P)*100

= 39%

Using this calculation we get the bleow 

( the read deal )


## The New Redesigned Visualization

![Alt text]()

(Tableau Public): 

This final visualization addresses all the above mentioned points. It shows how the original data was mis interpreted to highlight that there are more adults game than teens. But in actuality the data represented the usage of different devices by adults and teens to play games and that mostly adults use desktop/laptops whereas teens use gaming consoles. 

It also shows a deception where by considering the population of adults and teen gamers in USA, we can actually prove that there are more teen gamers than adults.

## Conclusion
We can claim from the data we have that 

The claim of the visualization is that 39% of adults are gamers, refuting the claim that 53% of adults are gamers. 


## References

https://www.forbes.com/sites/kevinanderton/2015/12/31/adults-vs-teens-video-game-edition-infographic/#7f55d43041b0

https://www.polygon.com/2015/4/14/8415611/gaming-stats-2015

https://www.census.gov/prod/cen2010/briefs/c2010br-03.pdf

https://www.statista.com/statistics/189582/age-of-us-video-game-players-since-2010/
