Analyzing US Traffic Accidents with Data Exploration and Visualization
This project delves into US traffic accidents, uncovering patterns and trends through Exploratory Data Analysis (EDA) and visualization.

Data Acquisition and Manipulation:

Import Libraries: Utilize pandas for data manipulation.
Load Dataset: Access the US accident data from Kaggle.
Exploratory Data Analysis (EDA):

Initial Glimpse: Display the first few rows of the data using head().
Data Quality Check: Identify and handle missing values (e.g., dropping rows with dropna()).
Data Dimensions: Determine the dataset's size (number of rows and columns) using shape.
Data Overview: Get a summary of data types and non-null counts using info().
Data Visualization:

Accident Distribution by City: Create a countplot (using sns.countplot()) to visualize the number of accidents in each city.
Temporal Patterns: Create a countplot of the "weather timestamp" to analyze how accidents are distributed across time.
State-wise Analysis: Generate a countplot of the "state" variable to understand accident distribution across different states.
Severity Breakdown: Create a countplot of the "severity" variable to visualize the distribution of accident severity levels.
Exploring Factors: Create countplots to explore potential contributing factors like timezone, wind direction, and astronomical twilight.
Severity and Wind Speed: Generate a boxplot (using sns.boxplot()) to compare wind speed across different severity levels and identify potential outliers.
Weather Conditions: Create a countplot of the "weather condition" variable to visualize the frequency of different weather conditions during accidents.
