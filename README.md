Data Analysis and Plotting of Hotel Ratings and Trip Type

Introduction
Hey, did you know hotel ratings can really make or break a business? High ratings attract more guests and boost revenue, while low ratings can scare people away
That's where data scientists come in. They analyze customer feedback and find ways to extract insights that can improve those ratings, which can make a huge difference.
It's not just about finding these insights but also sharing them in a way that business executives can easily understand. That’s why making good visualizations is key.
In this project, we study past data to find valuable insights. We will delve into the details of creating captivating visuals that reveal the patterns and trends.

Let's explore our dataset
Here's a brief description of the columns:

ID_USER: An identifier for each user.
USER_STATE: The state where the user is located (e.g., GA: Georgia, TX: Texas, NY: New York, OR: Oregon, VA: Virginia).
USER_TIMEZONE: The timezone of the user.
ID_HOTEL: An identifier for each hotel.
HOTEL_CITY: The city where the hotel is located.
HOTEL_STATE: The state where the hotel is located.
HOTEL_TIMEZONE: The timezone of the hotel.
Trip Type: Type of trip (e.g.,1. Business trip, 2. Vacation, 3. Family visit, 4. Conference, 5. Other leisure activities).
Rating: Rating given to the trip or hotel stay.

Univariate Analysis
Univariate analysis is the simplest form of data analysis. It involves only one variable. The "uni" in univariate means "one". This shows the analysis focuses on just one variable in the data.This is the univariate analysis section. We will make some basic plots using pandas and plot them for one variable.

Sample Questions:
1
Analyze Trip Type Distribution
Let's analyze the Trip Type column. As we know from our data dictionary, there are 5 types of trip types. If you forget, revisit our data dictionary at the top. Use value_counts() method on the Trip Type column. You will get 5 types. Store them in trip_type_counts.

2
Create a pie chart to identify the most popular Trip Type
Use the plot method to make a pie chart. Also, you need to give the title Most Popular Trip Type, and your autopct should be '%1.1f%%'
Note - To assist you, a figure and axis have already been created and use a semicolon (;) at the end to avoid garbage output in the plot.

3
Analyze Hotel City Distribution
The HOTEL_CITY column contains several cities where the hotels are present. Now, use the value_counts() method on the hotel city column and store it in the city_counts variable.

4
Create a bar chart to determine the most popular city where the highest number of hotels are present
Create a bar plot to see the highest number of hotels present in each city. Set xlabel as Hotel City, ylabel as Count, and finally, give the title as Most Popular Hotel Cities

5
Analyze Rating Distribution
The Rating column contains the ratings given by users for their hotel stays. Use the value_counts() method on the Rating column to get the count of each rating value. Store the resulting Series in the rating_counts variable.

This project is taken from DataWars. 
https://app.datawars.io/project/466e036d-f7f1-46ff-8e6c-779daf8327c2?page=1
