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




![Alt text]()

Then the focus shifted to the migration paths. The paths in which the migrations were maximum. Since too many countries would make the data too unreadable, top 3 countries were picked. This one too lacked information about the other countries.

![Alt text]()


## The New Redesigned Visualization

![Alt text]()

(Tableau Public): 


The final one that addresses all these points, shows the top 5 countries where people migrated to and also shows from which countries they come from. And also the top 5 countries where people emigrate out of and the countries they go to. Choosing the top 5 was done by looking at top 10, 20 countries. It was observed that beyond the top 5 the numbers from the other countries were quite insignificant. 
For example if one looks at the year 1995, it is very clear to see that United States was the country where most of the immigrants moved to. And It is also clear that the most number of people in this migration came from Mexico, Thailand, Guatemala and Philippines 
With these numbers from this chart we can now correlate other information with respect to migration. As one example that was stated above about the innovations(patents), we can get the number of immigrants into US from China and India and correlate it to the contribution of migrants from these two countries in the field of innovation. 

Below are some examples of such correlations. 
![Alt text](https://github.com/bhargavre/Dashboard_Labs/blob/master/Redesign/Dashboard%202.png)

## Conclusion

The claim of the visualization is flow of migration. And the idea behind the redesign was to make sure that the visualization keeps up to this claim with accurate, concreate and relevant data so that this data can be used to correlate it with other observations in society. The claim should not just be a proof of migration but should present data that can be useful for further analysis.


## References

