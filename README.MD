# Introduction



# Day One

## Day1Student.ipynb

This Python script, intended for execution in a Google Colab environment, provides a user-friendly interface for collecting and managing user information via a form. It uses the MongoDB database as the backend to store and retrieve data. The script initializes the connection to MongoDB, decoding a fallback base64-encoded URI if an environment variable for the connection is not available. It defines functions to fetch existing user data, add or update users, validate form inputs, and display success or error messages. The user form, built with the ipywidgets library, includes fields for entering a first name, second name, height, gender (with radio buttons), and date of birth (with a date picker). Submit and edit buttons allow users to add new entries or modify existing ones, with form validation to ensure required fields are filled.

Additionally, the script fetches and manipulates data stored in the MongoDB collection. It retrieves a list of user records and enables various analyses, such as counting the number of males, extracting user names, or calculating statistics like the minimum, maximum, and average height. This makes the script not only a data entry tool but also a basic data analysis utility, demonstrating MongoDB integration, data processing, and user interaction in a Colab environment.


## Day2Student.ipynb

This script is designed for use in Google Colab and facilitates uploading and analyzing student data stored in JSON or CSV formats. It uses the google.colab.files module to allow users to upload files directly into the Colab environment. The uploaded data is read into a pandas DataFrame for analysis and visualization. After loading the data, the script extracts the "Height" column and visualizes it using a line plot with matplotlib.pyplot, providing a simple way to inspect the distribution or trend of heights in the dataset. The script demonstrates basic file handling, data exploration, and visualization in Python.


## Day3Student.ipynb

This Python script, designed for use in Google Colab, combines several functionalities related to data fetching, visualization, and randomness. It first demonstrates fetching live weather data from the OpenWeatherMap API for Cluj-Napoca, Romania, processes the response to extract relevant fields like temperature, humidity, and wind speed, and displays this data in a pandas DataFrame. Next, it uses OpenStreetMap (OSM) via the osmnx library to fetch and visualize the street network around the city center of Cluj-Napoca within a specified radius, marking the city center on the map. The script also includes randomness-related functionalities such as generating random integers, floating-point numbers, and choices from a list, as well as performing a simulated random walk and visualizing it. Finally, it explores probability distributions by generating and plotting samples from uniform and normal distributions, comparing their characteristics visually using histograms.
