# PyBer_Analysis
# Purpose
I was given the task of pulling data from different cities and catagorizing them into city type to evaluate the quantities of drivers, fare costs, and dates. Given this information, I have seperated the data to calculate average cost of fares per ride for each city type , average fare per driver for the city type, and summarized it to show the difference in cost of Rural, Suburban, and Urban cities. 

# Process 
To begin evaluating the difference between the city types I had to:
- [x] calculate total counts : ride count, driver count, and fare count.
- [x] Use my total counts to determine average fares per drivers and average fare per ride.

<img width="599" alt="Screen Shot 2021-04-06 at 1 33 58 PM" src="https://user-images.githubusercontent.com/78769464/113761503-26edf580-96dd-11eb-8819-acbcde33f38a.png">

From here I created an entirely new dataframe that allowed me to narrow down a time frame from January 2019 through April 2019 and I was able to calculate the amount of fares each city type brought in weekly.

<img width="271" alt="Screen Shot 2021-04-06 at 1 39 25 PM" src="https://user-images.githubusercontent.com/78769464/113761834-8ba95000-96dd-11eb-9a77-2d47faa4e344.png">

Since looking at a bunch of numbers does not always display the gravity of difference from one city type to the next - I created a pivot table to visually display the difference between Rural, Suburban, and Urban city types and the comparison of fares brought in weekly. 

# Results

![PyBer_fare_summary](https://user-images.githubusercontent.com/78769464/113762337-19853b00-96de-11eb-9731-411ee39b3266.png)


# Summary

This data analysis allows you to accurately compare fare prices between Rural, Suburban, and Urban city types. 
   * The table demonstrates that the further away from the city you get - the more expensive the fare cost becomes but the least amount of drivers.
  * Suburban city types fall right in between the two other city types as far as Total Fares are shown. Looking at the amount of drivers (less than a quarter amount) and the ride count (less than half the amount) compared to Urban city types. Yet bringing in close to 50% total fares as Urban cities.
  * This data shows an abundance of drivers available within the urban city type but shows less cost of fares. The rates have to be competitive due to the amount of drivers. Less drivers in Rural city types causes the cost of fares to be higher - less supply.

## Recommendations
To even out the disparities among the different city types I recommend:
  * Increasing your supply of drivers to Rural cities so that the convenience in taking a fare versus driving increases therefore your demand will increase as well. This will decrease fare costs eventually but it will allow fares to be more accessible to rural areas.
  * Decreasing the amount of drivers you have saturated within the urban areas will allow the price to increase because the fare costs won't be as competitive. 
  * The suburban areas seem to be in a happy medium between the two other city types - I would suggest leaving the costs of fares the same but increasing the quantities of drivers to allow for more access.
