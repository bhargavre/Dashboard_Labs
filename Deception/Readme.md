## Introduction

He uses statistics as a drunken man uses lamp posts – for support rather than for illumination.
 - Andrew Lang

The same thing could be said of data. Data is extremely powerful and unfortunately, by manipulation, it can be used to support what we already believe or want to believe. Instead data should be used as a powerful source of knowledge and let it speak. The dashboards we design needs to do latter.



## My views on this visualization

Consider the following data set
Data Set 1
Category     |   Gaming Device    |       Usage Rate
-----------------------------------------------------
Adults	  |  Desktop or Laptop Computer	|  0.73
Adults	   |   Game Console	             | 0.53
Adults	    |  Mobile Device	             | 0.35
Adults	   | Portable Gaming Device	 |     0.35
Non-Parents|	Desktop or Laptop Computer|	  0.35
Non-Parents	|  Game Console	            |  0.22
Non-Parents	 | Mobile Device	            |  0.16
Non-Parents	 | Portable Gaming Device	    |0.1
Parents	|    Desktop or Laptop Computer	 | 0.45
Parents	 |     Game Console	              |0.41
Parents	  |    Mobile Device	              |0.25
Parents	   |   Portable Gaming Device	 |   0.21
Teens	      |Desktop or Laptop Computer	|  0.76
Teens	       | Game Console	             | 0.89
Teens	        |Mobile Device	             | 0.5
Teens	      |  Portable Gaming Device	   | 0.62

The infographic that was created using this data set claimed that 53% of adults are gamers. This claim can be miss-constructed from the above data by filtering on Desktop usage and Adults, like we show below.

 
Data Set 1 only gives information about what kind of devices each type of gamers use. For example it only says that of all the adult gamers, 53% of them use Desktop or Laptops for gaming. There is no data about the total number of gamers or the proportion of adult vs teens. From this data set the only information that can be gleaned is the following:
 
The claim that 53% of adults from this data is a clear miss representation of data. [as was done in https://www.forbes.com/sites/kevinanderton/2015/12/31/adults-vs-teens-video-game-edition-infographic/#7f55d43041b0]
One cannot say if this is true or not based on the data available.

In order to check if this claim has any credibility, one needs to get more data. 

•	What percent of US population are gamers?
•	What percent of US population are adults?
•	What percent of gamers in US are adults?



## Reason for Redesign

The Goal here is to redesign the visualization to strengthen the existing claim that reads "Flow of Global Migration"
For an audience who is interested in migration, the existing visualization fails to give details and the information it presents is very overwhelming. There is no conclusion the user can draw from this visualization. The goal for the redesign was to leave the user with concrete information about the flow of people. The user should be able to say that in 2000 US was the most popular destination for migrants and the migrants came from China, India and Mexico. It should have enough data to interest a general reader and detailed enough to for a journalist or an economist to use this data and correlate it to other data. 
For example, there have been a lot of studies that look at patterns of employment, education, economic growth, innovation over the years. 

![Alt text](https://github.com/bhargavre/Dashboard_Labs/blob/master/Redesign/Patents.png)

The redesigned visualization will point out pattern of movement of people into a country very clearly and this information can be used to correlate it with the data presented above. This will be shown later after the redesigned visualization has been introduced.


## Data Wrangling

The data was 2.376 MB with information about all the countries and regions and number of people coming in and out of the region in the years of 1990,1995, 2000 and 2005.  This data did not contain Cities/Areas which made it difficult to understand the flow from one region to the same region. Hence the flow within countries was not considered. The challenge with so much of data is visualization. Not all of this should be used in the dashboard because it will just overwhelm the user looking at the visualization. The right data needs to be picked and synthesized in order to give some meaningful data to the user.


## Visualization Process

There were many different visualizations that were tried. The first one focused on the country where the most of the immigration happened and went into the details of the effects of this migration in terms of employment, education, economy etc. But that meant there was no information about the other countries and the migration patterns there. 

![Alt text](https://github.com/bhargavre/Dashboard_Labs/blob/master/Redesign/Migration%20to%20US.png)

Then the focus shifted to the migration paths. The paths in which the migrations were maximum. Since too many countries would make the data too unreadable, top 3 countries were picked. This one too lacked information about the other countries.

![Alt text](https://github.com/bhargavre/Dashboard_Labs/blob/master/Redesign/Top%20Migration%20Paths.png)


## The New Redesigned Visualization

![Alt text](https://github.com/bhargavre/Dashboard_Labs/blob/master/Redesign/Dashboard%203.png)

(Tableau Public): https://public.tableau.com/views/Redesign-GlobalFlowofMigration/Dashboard3?:embed=y&:display_count=yes&publish=yes


The final one that addresses all these points, shows the top 5 countries where people migrated to and also shows from which countries they come from. And also the top 5 countries where people emigrate out of and the countries they go to. Choosing the top 5 was done by looking at top 10, 20 countries. It was observed that beyond the top 5 the numbers from the other countries were quite insignificant. 
For example if one looks at the year 1995, it is very clear to see that United States was the country where most of the immigrants moved to. And It is also clear that the most number of people in this migration came from Mexico, Thailand, Guatemala and Philippines 
With these numbers from this chart we can now correlate other information with respect to migration. As one example that was stated above about the innovations(patents), we can get the number of immigrants into US from China and India and correlate it to the contribution of migrants from these two countries in the field of innovation. 

Below are some examples of such correlations. 
![Alt text](https://github.com/bhargavre/Dashboard_Labs/blob/master/Redesign/Dashboard%202.png)

## Conclusion

The claim of the visualization is flow of migration. And the idea behind the redesign was to make sure that the visualization keeps up to this claim with accurate, concreate and relevant data so that this data can be used to correlate it with other observations in society. The claim should not just be a proof of migration but should present data that can be useful for further analysis.


## References
http://conversableeconomist.blogspot.in/2014/01/

http://voxeu.org/article/global-economic-slumps-and-migration

http://www.nber.org/papers/w13229.pdf

http://www.pewhispanic.org/2015/09/28/chapter-3-the-changing-characteristics-of-recent-immigrant-arrivals-since-1970/

http://www.global-migration.info/

https://en.wikipedia.org/wiki/Human_migration

https://www.nap.edu/read/12860/chapter/12

http://peoplemov.in/#t_AR

http://flow.mmg.mpg.de/

http://metrocosm.com/global-immigration-map/

http://www.iom.int/world-migration
