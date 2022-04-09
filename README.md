# City Bike-sharing Analysis using Tableau 
# Overview
In this project, I analyzed bike-sharing data from New York City during the summertime, particularly the month of August. I wanted to gain an idea of what type of user frequents a bike-sharing business, what was the average bike checkout time, which genders utilized bike-sharing more, and what is their average trip duration. The analysis I completed was vital to modeling a bike-sharing business for a proposal in the city of Des Moines.
## Preprocessing
Prior to creating the visualizations in Tableau, I used the Pandas dependencies in Python to convert the "trip duration" to a date-time format. In addition, in Tableau, I created a 'calculated field' that converts numbers to strings in the context of gender.  In the calculated field, I created a for loop that looped through the numbers 0, 1, and 2. Each number corresponds to a string :

**Number to String**

<img width="332" alt="Number_to_String" src="https://user-images.githubusercontent.com/87162266/149636808-c71e686a-09f9-4f8b-9d35-10099579ec01.PNG">

# Results
[TABLEAU STORY](https://public.tableau.com/app/profile/diamond.washington/viz/NYCCitiBike6/TripsbyGenderWeekdayperHour?publish=yes)
# Conclusion
Locations within a 5-minute bike ride are ideal for bike-sharing. The average trip duration is 5 minutes for both males and females.  5 pm and 6 pm are the densest times for bike-sharing on all weekdays but Wednesday.  Males use bike sharing more than any gender.  Bike-sharing hours are the densest at 7 am and 5 pm for males. This suggests bike-sharing is the transportation used for commuting to and from work.  Furthermore, the male population makes up 72.2 percent of subscribers in the NYC bike-sharing business. Female bike share usage trends are similar to male trends, however, are three times less in population.  Going forward, I’d include a visual that conveyed the average trips in NYC for every month. August is a hot time of the year, perhaps looking at August is giving an overzealous prediction of performance. Stakeholders may consider a seasonal bike-sharing business with further analysis.  In addition, I’d include a visual that labels the types of businesses near the popular starting and ending point. There may be a need for local business development prior to the bike-sharing business performing well in Des Moines.


