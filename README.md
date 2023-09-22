# Weather Analysis with Python

## Introduction

This project explores how weather changes as someone moves closer to the equator. By leveraging Python, APIs, and JSON data, I aim to answer a fundamental question: "What is the weather like as I approach the equator?"

## Part 1: WeatherPy

### Visualizing Weather Relationships

I begin by visualizing the weather of over 500 cities worldwide and their relationship with latitude. The following scatter plots help me understand these relationships:

-   **Latitude vs. Temperature:** How does temperature change with latitude?
-   **Latitude vs. Humidity:** Is there a correlation between humidity and latitude?
-   **Latitude vs. Cloudiness:** Does cloudiness vary with latitude?
-   **Latitude vs. Wind Speed:** How does wind speed relate to latitude?

### Understanding the Data

I compute linear regression for each relationship, dividing the data into the Northern and Southern Hemispheres. Linear regression plots include the regression line, formula, and r-values. The plots I create are:

-   **Northern Hemisphere: Temperature vs. Latitude**
-   **Southern Hemisphere: Temperature vs. Latitude**
-   **Northern Hemisphere: Humidity vs. Latitude**
-   **Southern Hemisphere: Humidity vs. Latitude**
-   **Northern Hemisphere: Cloudiness vs. Latitude**
-   **Southern Hemisphere: Cloudiness vs. Latitude**
-   **Northern Hemisphere: Wind Speed vs. Latitude**
-   **Southern Hemisphere: Wind Speed vs. Latitude**

After each pair of plots, I explain the implications of the linear regression models and any significant findings.

## Part 2: VacationPy

### Planning My Ideal Vacation

In this section, I use my weather data analysis to plan future vacations based on preferred weather conditions. Here's what I do:

1.  **Creating a Humidity Map:** I created a map displaying points for every city in my dataset, where the point size represents humidity. This helps me identify regions with comfortable humidity levels.
    
2.  **Finding Ideal Weather Conditions:** Narrowed down my dataset to find cities with ideal weather conditions, considering factors like maximum temperature, wind speed, and cloudiness.
    
3.  **Locating Nearby Hotels:** I created a new DataFrame, `hotel_df`, to store information about cities, countries, coordinates, and humidity. For each city, I use the Geoapify API to find the nearest hotel located within 10,000 meters of its coordinates.
    
4.  **Visualizing My Vacation:** Add hotel names and countries as additional information in the hover message for each city on the map. This allows one to plan vacations based on preferred weather conditions while exploring different cities.
    

## Conclusion

This project showcases the power of Python, APIs, and data visualization techniques in exploring and analyzing weather data. Understanding weather patterns and planning vacations based on weather preferences are essential applications of this analysis.

## Reference

For this analysis, I utilized the [citipy Python](https://pypi.python.org/pypi/citipy), the [OpenWeatherMap API](https://openweathermap.org/api) to fetch weather information, and applied problem-solving skills to construct a comprehensive model of weather patterns across various cities.
