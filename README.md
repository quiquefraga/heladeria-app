# Ice Cream Production Optimization App

## Overview

This application helps ice cream producers optimize their production based on weather conditions and predicted demand increases. By inputting a city, the app estimates the temperature and provides recommendations for increasing production of different ice cream flavors.

## How it Works

1. **Temperature Simulation:** The app simulates the temperature for a given city using a random number generator between 10 and 35 degrees Celsius. (Note: This is for demonstration purposes; a real-world application would use a weather API for accurate temperature data).
2. **Demand Calculation:** Based on the temperature, the app calculates the estimated increase in demand for ice cream. Higher temperatures lead to higher demand.
3. **Production Recommendations:** The app then provides recommendations for increasing the production of three ice cream flavors: "Triple Tentación", "Mil Hojas", and "Dulce de Leche". These recommendations are based on the calculated demand increase and predefined percentages for each flavor.
4. **User Interface:** The user interacts with the app through a simple web interface built using Gradio. They input a city name and receive the production recommendations as output.


## Installation and Usage

1. **Install Dependencies:**
