# Introduction



# Day One

## Day1Student.ipynb

This Python script, intended for execution in a Google Colab environment, provides a user-friendly interface for collecting and managing user information via a form. It uses the MongoDB database as the backend to store and retrieve data. The script initializes the connection to MongoDB, decoding a fallback base64-encoded URI if an environment variable for the connection is not available. It defines functions to fetch existing user data, add or update users, validate form inputs, and display success or error messages. The user form, built with the ipywidgets library, includes fields for entering a first name, second name, height, gender (with radio buttons), and date of birth (with a date picker). Submit and edit buttons allow users to add new entries or modify existing ones, with form validation to ensure required fields are filled.

Additionally, the script fetches and manipulates data stored in the MongoDB collection. It retrieves a list of user records and enables various analyses, such as counting the number of males, extracting user names, or calculating statistics like the minimum, maximum, and average height. This makes the script not only a data entry tool but also a basic data analysis utility, demonstrating MongoDB integration, data processing, and user interaction in a Colab environment.


## Day2Student.ipynb

This script is designed for use in Google Colab and facilitates uploading and analyzing student data stored in JSON or CSV formats. It uses the google.colab.files module to allow users to upload files directly into the Colab environment. The uploaded data is read into a pandas DataFrame for analysis and visualization. After loading the data, the script extracts the "Height" column and visualizes it using a line plot with matplotlib.pyplot, providing a simple way to inspect the distribution or trend of heights in the dataset. The script demonstrates basic file handling, data exploration, and visualization in Python.


## Day3Student.ipynb

This Python script, designed for use in Google Colab, combines several functionalities related to data fetching, visualization, and randomness. It first demonstrates fetching live weather data from the OpenWeatherMap API for Cluj-Napoca, Romania, processes the response to extract relevant fields like temperature, humidity, and wind speed, and displays this data in a pandas DataFrame. Next, it uses OpenStreetMap (OSM) via the osmnx library to fetch and visualize the street network around the city center of Cluj-Napoca within a specified radius, marking the city center on the map. The script also includes randomness-related functionalities such as generating random integers, floating-point numbers, and choices from a list, as well as performing a simulated random walk and visualizing it. Finally, it explores probability distributions by generating and plotting samples from uniform and normal distributions, comparing their characteristics visually using histograms.


## Day4Student.ipynb

This Python script, designed for use in Google Colab, demonstrates how to analyze the relationship between temperature and humidity using real-time weather data. It fetches a 5-day weather forecast for a specified city (default: Cluj-Napoca) from the OpenWeatherMap API, extracting temperature and humidity data for each time point in the forecast. Using the scipy.stats.pearsonr function, it calculates the Pearson correlation coefficient to quantify the strength and direction of the linear relationship between these two variables. The script also visualizes this relationship by plotting a scatter plot of temperature versus humidity, providing a clear view of their interaction. This workflow combines data fetching, statistical analysis, and visualization to explore environmental data trends.

## Day5Student.ipyn

This Python script, designed for use in Google Colab, introduces fundamental concepts of data analysis and machine learning using numpy, matplotlib, and scikit-learn. It consists of three exercises:

Exercise 1: Understanding Distributions
This exercise demonstrates the difference between uniform and normal distributions by generating 10,000 random numbers from each distribution and visualizing their characteristics. The uniform distribution generates numbers evenly spread within a range, while the normal distribution follows a bell curve centered around the mean with a given standard deviation.

Exercise 2: Linear Regression
Using weather data from a CSV file (weather_data.csv), this exercise guides users to calculate regression coefficients with LinearRegression from scikit-learn. The goal is to model the relationship between input features and target variables, demonstrating how linear regression can predict trends in real-world data.

Exercise 3: Weather Data Clustering
This exercise involves classifying seasonal weather data from another CSV file (seasonal_weather_thw_Cluj-Napoca.csv) using the K-Means clustering algorithm. It showcases unsupervised learning techniques to group similar data points, enabling users to identify weather patterns.

The script combines statistical analysis, regression modeling, and clustering, making it an excellent introduction to machine learning concepts applied to real-world datasets.


