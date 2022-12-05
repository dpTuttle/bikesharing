# Bikesharing Data Analysis

### Overview of the Statistical Analysis:
 - Using data gathered by CitiBike (Lyft) for the month of August 2019, the purpose of this analysis is to glean data insights that may prove useful for investors in making the decision to implement a similar bike sharing program in Des Moines, IA. 
 
 The study leverged three key types of data:
 
 - **Demographic:** To understand who the target audience is for a potential bike sharing program and the business model that would prove most effective for project longevity. 
      
 - **Geographic:** To understand the most effective locations to place bike terminals and what are potential users most utilizin the bike share for.
      
 - **Temporal:** To understand the duration of rides, optimal times for bike usage and preferred operating days
      
  The study used the following data tools:
  
  - Python 3.7.6
  - Pandas Dataframes
  - Tableau
  
 The final data analysis is presented below as a [Tableau story](https://public.tableau.com/app/profile/demetrice.tuttle/viz/CitiBike_Challenge_14_DPT/NYCStory?publish=yes) made public.  

### Results:

The first page in the story provides the demographic data alluded to above. There were over 2M rides in August 2019. Over 1.9M customers were subscribers, and just over 400K were day-of customers. The gender breakdown is roughly 65% male, 25% female and 10% undefined:

![Story_1](https://github.com/dpTuttle/bikesharing/blob/main/Story_1.png)

Next, we move to temporal data analysis. The following story pane shows that a majority of all rides last between 0 - 10 minutes:

![Story_2](https://github.com/dpTuttle/bikesharing/blob/main/Story_2.png)

The proceeding pane continues our temporal data analysis to demonstrate the usage curve across genders. The trend is common between both genders although there are more FEMALE riders with longer ride durations (up to 15 and 20 mins):

![Story_3](https://github.com/dpTuttle/bikesharing/blob/main/Story_3.png)

The following story panes provide us with geographic data, noting the most popular starting locations around Manhattan. Using Tableau background data, we can see that the nieghborhoods of Tribeca, Union Square, and Chelsea are populare starting points. It is also critical to note that these starting points are near major metro stations -- hinting that the bike share program may be a solution for the 'final mile' transit problem:

![Story_4](https://github.com/dpTuttle/bikesharing/blob/main/Story_4.png)

The next pane continues the geographic data presentation and demonstrates that the same neighborhoods and transit areas are popular drop off points. This may suggest that riders are using the bikes for short, close-to-home errands, OR, that most rides originate and end at the these critical transit stops:

![Story_5](https://github.com/dpTuttle/bikesharing/blob/main/Story_5.png)

Our 6th story pane shifts the data analysis back to temporal to help us understand the usage acros the day and days of the week. The below heat mpa suggests that during the weekends, most usage is between 8AM and 6PM (perhaps because of an influx of tourists), however, during the weekdays, the most popular usage occurs in the early morning (between 6AM and 9AM) and in the evening (between 4PM and 7PM), suggesting that many users are utilizing the bikes for work commutes. This is also striking considering NYC is a popular tourists destination. The consistent weekday usage may also suggest that the program is largely used by locals (perhaps becuase the lack of on bike GPS would mean one must know where they are going already):

![Story_6](https://github.com/dpTuttle/bikesharing/blob/main/Story_6.png)

We complete the same analysis across genders and find that (congruent with our rider demographic data), more MALES use the bike share program and are heavy weekday work commute users. Interestingly though, Wednesday's are a light usage day across both genders:

![Story_7](https://github.com/dpTuttle/bikesharing/blob/main/Story_7.png)

Lastly, we analyze usage across genders and customer type. The data here suggests that MALE subscribers are use the bike share program the most and heavily on Mondays, Tuesdays, Thursdays and Fridays. Perhaps these are heavy traffic days and the bikes make for easy commutes. FEMALE subscribers are consistent weekday users as well. Most non-subscription customers use the bike share program on Saturdays (again, suggesting that these users may be tourists).


### Summary:

- Overall, the data suggests that a subscription based bike share program centered on solving final mile transit or commute issues may be most effective for any city. The terminals should be located near heavy traffic or critical public transit hubs. 

- To better understand usage, two additional visuals would help:
1.) a comparison between ridership and weather (to understand if the local weather is a limiting factor for usage)
2.) a comparison between start and stop locations for high usage bikeids to predict potential failure modes and the need for downtime (is that after 5 station usage, 50 hrs of riding, etc?).

