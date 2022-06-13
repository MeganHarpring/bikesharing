# Bikesharing

### Overview of Analysis:

The purpose of this analysis is to sell the idea of a bikesharing company in Des Moines, Iowa to some investors. We need to show some good data visualizations so that it is easy for the investors to understand and easy for them to see the benefits of a bike-sharing program in Des Moines. Specifically, one of the investors would like to see a bike trip analysis and to do this I had to write a python code in order to convert the datatype of the "tripduration" column from an integer to a datetime datatype. Once we have a converted dataframe we will create visualizations to show the length of time that bikes are checked out for all riders and genders, the number of bike trips for all riders and genders for each hour of each day of the week, and the number of bike trips for each type of user and gender for each day of the week. We will then create a story in Tableau to pitch to investors.

### Results:
<img width="487" alt="Pic 1" src="https://user-images.githubusercontent.com/100392991/173268402-cf71ef9a-5626-4cbc-8297-653ec26bc5a9.PNG">
Above you will see that we have a graph that shows the length of time that bikes are checked out for all riders. In New York City, approximately, 147,000 riders rode their bike for 5 minutes and majority of riders ride their bikes for 25 minutes or less. 


<img width="514" alt="Pic 2" src="https://user-images.githubusercontent.com/100392991/173269447-5b10f15a-169a-4195-beea-575e7605588d.PNG">
In the above graph we did the same thing but broke it down by gender: Male, Female, or Unknown. We can see that males clearly ride and take more bike trips by almost 3x that of females. The graph shows a very similar pattern to the first one - majority take bike trips less than 25 minutes. 

<img width="503" alt="Pic 3" src="https://user-images.githubusercontent.com/100392991/173269741-14386391-7e73-4bb9-8882-9c1a5432ec13.PNG">
This graaph shows us the busiest times for people to rent bikes through out the week. It shows that the busiest times seem to be the morning work commute (7am-9am) and the home commute (4pm-7pm). The weekends seem to be busy most of the day (9am-7pm).


<img width="515" alt="Pic 4" src="https://user-images.githubusercontent.com/100392991/173270245-1eb66f41-9626-4cc7-b960-b1aba6e08da7.PNG">
This graph is the same as the one before but breaks down the days of the week and times by gender. This shows us a similar pattern as far as busy times and we can see that males far exceed the number of bike trips compared to females or unknown. 


<img width="515" alt="Pic 5" src="https://user-images.githubusercontent.com/100392991/173270527-63af283e-d76d-4171-ab0a-5a632ec40497.PNG">
This graph breaks up usertypes (Customers or Subscribers) by gender and days of the week. It seems as though majority of the users are Male Subscribers who take the most trips during the week. My guess is that a huge chunk of citibike users are Males who subscribe because they ride a bike to and from work everyday. 


<img width="514" alt="Pic 6" src="https://user-images.githubusercontent.com/100392991/173270973-c7e8ca69-bd8f-4db5-9918-1602e69ff1e2.PNG">
<img width="530" alt="Pic6 1" src="https://user-images.githubusercontent.com/100392991/173271053-b8f13e7b-9524-4bd5-ac67-90216eb79574.PNG">
<img width="512" alt="Pic 6 2" src="https://user-images.githubusercontent.com/100392991/173271069-f68f2fe9-1f03-4191-ab79-f29448c6912c.PNG">
 In the above three pictures I made a graph that breaks down the number of trips by hour each day. We can see that Thursdays, Fridays, and Saturdays are pretty busy. This chart will also help determine when the best time to do bike maintenance. 
 
 
<img width="516" alt="Pic 7" src="https://user-images.githubusercontent.com/100392991/173271715-e22fd315-1391-451d-81de-cf5dbef28e75.PNG">
Lastly, this graph above shows us the ages of riders and which ages take the most bike trips. We can see that 52/53 year olds are largly the bike riders in New York City and majority of all riders are born after 1960.


### Summary:

Even though New York City is a much bigger city and a larger tourist destination compared to Des Moines, Iowa I think we can use these graphs as a general reference to target our customer base (Males) and we can use these graphs to determine when the busiest times/slowest times will be. It will also be helpful as far as marketing and deciding the cost for the bikes to see that subscribers are the main users - thus, we can come up with some kind of sales deal that is targeted to working males around the age of 52 and younger. 
We also should consider making a visual to show which riders are tourist and which live in the city or work in the city. Another thought for a visual is to consider how many riders make multiple stops; stop their trip to make a stop somewhere and then begin another trip when they are done. 


