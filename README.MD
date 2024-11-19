Start here

# Day One

Day1Student.ipynb

This Python script, intended for execution in a Google Colab environment, provides a user-friendly interface for collecting and managing user information via a form. It uses the MongoDB database as the backend to store and retrieve data. The script initializes the connection to MongoDB, decoding a fallback base64-encoded URI if an environment variable for the connection is not available. It defines functions to fetch existing user data, add or update users, validate form inputs, and display success or error messages. The user form, built with the ipywidgets library, includes fields for entering a first name, second name, height, gender (with radio buttons), and date of birth (with a date picker). Submit and edit buttons allow users to add new entries or modify existing ones, with form validation to ensure required fields are filled.

Additionally, the script fetches and manipulates data stored in the MongoDB collection. It retrieves a list of user records and enables various analyses, such as counting the number of males, extracting user names, or calculating statistics like the minimum, maximum, and average height. This makes the script not only a data entry tool but also a basic data analysis utility, demonstrating MongoDB integration, data processing, and user interaction in a Colab environment.


