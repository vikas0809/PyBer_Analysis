# PyBer_Challenge

## Overview & Purpose

This project is to visualize the rideshare data for a Pyber,a ride sharing company to help them to improve their ridesharing services.This will further help the company to understand the cities and their riding trends.To do this they have provided us two different data files which have information about the cities and the rides. We will do our analysis process on these two files and merge them together to create a summary Data file. We will also create a line chart graph to visualize the weekly graph of rides by the city type that is urban, suburban, rural.

We will use python,Matplotlib and Pandas libraries to create data-frames and visualize the data.

## Results

### Summary DataFrame


We read the data from two different files and concluded into one data frame.

![](Resources/1.png)

- The highest revenue generating city type is Urban which is $39,854.38.
- Urban revenues is more than twice of revenue of suburban city type which sits at $19,356.33.
- The total number of urban rides are 1625 which is 1500 more rides than rural rides.This concludes that urban rides are 13x the rural rides.
- Same scenario in case of number of drivers,the total number of urban drivers.Urban drives are 31 times higher than rural count of drivers.Sub urban       driver count is aproximately 0.25 of the urban driver count.
- According to the basics of the bussiness,more the volume lower the average price of the sale gets.The average ticket of the urban ride is lowest         averageing $25.53 per ride.The lowest revenue genrating categoty has highest average ticket of $34.62


### Line chart visualtization

![](Analysis/image11.png)

Visualization is great way for anyone to easily understand the data and its trends.
- Busiest week for the city types is third week of Feburary.
- There is sharp decline in revenue for all city types in last week of Feburary.
- Revenue range for Urban: 1600-2500(USD)
- Revenue range for Suburban: 600-1400(USD)
- Revenue range for Rural: 0-500(USD)
- The revenue increase for Urban cities is gradual with time.

## Detailed Analysis

### Using Magic methods
      
      # Add Matplotlib inline magic command
      %matplotlib inline

### Adding Dependencies
    
    # Dependencies and Setup
    import matplotlib.pyplot as plt
    import pandas as pd
    # Import the style from Matplotlib.
    from matplotlib import style

### Loading and Reading CSV files

    # File to Load
    city_data_to_load = 'Resources/city_data.csv'
    ride_data_to_load = 'Resources/ride_data.csv'

    # Read the City and Ride Data
    city_data_df = pd.read_csv(city_data_to_load)
    ride_data_df = pd.read_csv(ride_data_to_load)




