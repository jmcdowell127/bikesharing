# Bike-Sharing

## Overview
The purpose of this project was to figure out if a bike rental business, Citi Bike,  is worth investing into in Des Moines, Iowa. Citi Bike is very popular in New York City, so I used trip data from the month of August to create a few graphs and visualizations to support a solid business proposal in Des Moines in order to convince investors of its merrit. The visualizations created for this analysis are as follows:
* Show the length of time that bikes are checked out for all riders and genders.
* Show the number of bike trips for all riders and genders for eah hour of each day of the week.
* Show the number of bike trips for each type of user and gender for each day of the week.
* Show the peak riding hours in the month of August.
* Show the gender breakdown of active riders.

## Results
__Checkout Times for Users__ - *All trips are less than 1 hour with the majority being between 5 to 30 minutes.*
 * <img width="622" alt="checkout_users" src="https://user-images.githubusercontent.com/85372441/134232118-119e081c-5d63-42cb-8894-70ddf6f392d8.png">
__Checkout Times by Gender__ - *The vast majority of users are male.*
* <img width="726" alt="checkout_gender" src="https://user-images.githubusercontent.com/85372441/134232349-f309f1b3-ef55-491e-8dc1-56d9cf6946b8.png">
__Trips by Weekday per Hour__ - *The bulk amount of trips are taken between two time frames (6 AM to 9 AM & 4 PM to 8 PM).*
* <img width="243" alt="trips_weekday" src="https://user-images.githubusercontent.com/85372441/134232485-f2904e56-82a2-4d53-be07-9c92e15e053f.png">
__Trips by Gender (Weekday per Hour)__ - *While the majority of bike users are men, both genders seem to have the same riding routines throughout the day.*
* <img width="766" alt="trips_gender" src="https://user-images.githubusercontent.com/85372441/134232562-9c5e5f43-22ef-4d65-af52-ce6706b090af.png">
__User Trips by Gender by Weekday__ - *There are vastly more subscriber based users compared to nonsubsciber(customer) users. Slowest days for business appear to be Sunday, Wednesday & Saturday.*
* <img width="723" alt="trips_users" src="https://user-images.githubusercontent.com/85372441/134232708-e78d1c60-329c-432c-9321-79bd5706e03a.png">
__August Peak Hours__ - *The best times for maintenance based on peak hours would be between 21 AM & 5 AM.*
* <img width="724" alt="august" src="https://user-images.githubusercontent.com/85372441/134232790-7e5bc970-b7ff-4248-9977-34a9ddcb01ea.png">
__Gender Breakdown__ - *There are 1,530,272 male users(orange), 588,431 female users(blue), and 225,521 unkown users(red).*
* <img width="633" alt="genders" src="https://user-images.githubusercontent.com/85372441/134232875-69e3c53e-77d0-4fee-b8fe-fcc06e6488c0.png">

## Summary
Based on my analysis I have come to a few conclusions. The best times for completing bike maintenance are from 12 AM to 5 AM, this is because the peak hours of usage start around 7 AM and does not slow down much until 11 PM. While the data shows that the large majority of users are men, both genders are using Citi Bikes for an average trip time between 5 to 30 minutes with none exceeding 1 hour. Weekdays are where the majority of business is being had with Saturday, Sunday and Wednesday being the slowest days. 
__Recommendations__
I would recommend adding a couple more visualizations with the given dataset.
1. A visualization that displays the the number of bikes availiable (bikeid) compared to the number of users (tripdata csv) to see if there is adequate amount of bikes for the customer/subscriber base.
2. A visualization that displays the age of users (birth year) compared to starting locations (start station latitude + start station longitude) to see how closely they are to colleges, universities, and downtown areas. 
