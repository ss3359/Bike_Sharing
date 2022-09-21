# Bike_Sharing

# Overview 
This is a Tableau Story displaying bike sharing data poresented by Citi-Bike in Des Moines, Iowa. Not only we used Tableau to display data as a charts, heatmaps, and bubble charts, we have used Pandas to change the datatypes of the trip duration to a datetime. 

# Purpose 
We want to convince investors that a solid bike-sharing program in Des Moines is a very solid one. However, to enhance our porposal to the investors, we delve into a deep analysis visualizing the trip durations by gender, time, and the best place to start your bike sharing trip. 

# Results 
We should mention that the csv files in question cannot be uploaded to GitHub since the files exceed the minimum requirement to upload the files on this site. The csv files we have used was provided by Citi Bike Trip Data for 2019. For the City Bike Data in New York City, here is the website to access the data as a csv file: https://ride.citibikenyc.com/system-data. 

[Click here to access Tableau Story and Sheets we created.](https://public.tableau.com/app/profile/stephen.sivetts/viz/CityBikeProjectUSETHISONE/CitiBikeAnalysisStory?publish=yes) 

The first sheet we presented is the Checkout Time For Users and the second sheet is the Checkout Time browken down by Gender. The rows are labeled in Military Time.

## Figure 1 (Checkout Time by User)

<img width="1576" alt="Screen Shot 2022-09-21 at 9 40 56 AM" src="https://user-images.githubusercontent.com/104328106/191549268-38ffb060-c0b4-4a36-a624-1823483effb5.png">

## Figure 2 (Checkout Time By Gender)

<img width="1591" alt="Screen Shot 2022-09-21 at 9 41 36 AM" src="https://user-images.githubusercontent.com/104328106/191549406-8c86fe90-e77c-46b2-9cbc-e1930bec231b.png">

The nest figures displays "Heatmap" charts displaying the most and least amount of trip durations broken down by each hours of the days of the week. 

## Figure 3 (Trip By Weekday Each Hour)

<img width="1577" alt="Screen Shot 2022-09-21 at 9 43 48 AM" src="https://user-images.githubusercontent.com/104328106/191549945-4646221b-c897-4d71-91b7-1d98d383a30b.png">

## Figure 4 (Trip By Gender Weekday Per Hour)

<img width="1530" alt="Screen Shot 2022-09-21 at 9 46 33 AM" src="https://user-images.githubusercontent.com/104328106/191550604-7ffe7306-15e8-4c9d-9a70-03a804f723a9.png">


The next sheet presents the Trip Duration broken down by User Type and Gender each day of the week. A customer is a new person that is renting a Citi Bike. However a subscriber is an existing customer that rented a Citi Bike in Des Moines. 

## Figure 5 (User Trip By Gender)

<img width="1481" alt="Screen Shot 2022-09-21 at 9 50 02 AM" src="https://user-images.githubusercontent.com/104328106/191551375-df1beea3-c94c-43a5-abb0-bd41335975c7.png">

This is some of the sheets presented in the Tableau Story presenting Bike Sharing Data in Des Moines, Iowa during the year 2019. 

# Summary

Here are the details of what the pieces of data is representing. In Figure 1, we see that the checkout time is after Midnight. This is the time where not a lot of bikers are renting the bikes in Des Moines. The majority of people renting the Citi Bikes are males which is presented in Figure 2. The interesting sheets in this story is the "Heatmap" charts displaying the number of trips in each hour of the day of the week. In Figure 3, we see the best times to rent a Citi Bike is on any weekday between the times 8:00am, 5:00pm, and 6:00pm. Any day of the week between 12:00 modnight to 5:00am is not the best time to rent a Citi Bike. What was interesting is the number of trips during the evening on the weekends is lower than the number of trips generated in the weekday at that exact timeframe. Figure 4 shows the majority of trips are rented out by males in that said timeframe. The highest trip durations are made in that same timeframe by Females as well. However, the count is lower than males. What is wrong with this portion of the story is it may not convince other investors to be part of the CitiBike sharing program in Iowa. We may need more information accurately describing who, why, and where the customers are renting from CityBike. 

For example, here is a chart that overviews the average trip duration by the customer's birth year. Here is a chart that displays the average trip duration for each customer in New York City by birth year. 

## Figure 6
<img width="1533" alt="Screen Shot 2022-09-21 at 11 21 27 AM" src="https://user-images.githubusercontent.com/104328106/191570308-aca02507-070e-4caf-aaf5-3268c1a0d2cb.png">

There is a fallacy that this chart is displaying. The years of the charts dispays birth years between 1885 through around 2003 or 2004. CitiBike was founded in 2013. It may be comic relief but it is not possible somebody born in 1885 is renting out the bikes. However, this may be an improvement to the story needed to convince investors to invest to the program. 

Here is another sheet displaying the top starting location where people rent out the bikes in New York City. 

<img width="1466" alt="Screen Shot 2022-09-21 at 11 30 24 AM" src="https://user-images.githubusercontent.com/104328106/191571903-2ffe542e-141e-4c0b-a7a9-25d0612fa5f0.png">

We can clearly see the top location of renting out the bikes are in Manhattan, a borough in New York City. There are some locations where people rent bikes in the Bronx, and Queens, and in Brooklyn. The fallacy of this sheet is it is relying on data containg customers having irregular birthyears. This would be called an outlier. We would have to do more data cleaning and parsing to get the most accurate description of where customers are renting the CitiBikes.  
