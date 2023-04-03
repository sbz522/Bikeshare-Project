# Bikeshare-Project
This project uses Python to analyze bikeshare data from three major cities in the United States: Chicago, New York City, and Washington, DC. The project was completed as part of the Udacity Data Analyst Nanodegree program.

# Data
The data used in this project was provided by Motivate, a bike share system provider for many major cities in the United States. Randomly selected data for the first six months of 2017 was used for all three cities. The data includes the following columns:

Start Time (e.g., 2017-01-01 00:07:57)
End Time (e.g., 2017-01-01 00:20:53)
Trip Duration (in seconds - e.g., 776)
Start Station (e.g., Broadway & Barry Ave)
End Station (e.g., Sedgwick St & North Ave)
User Type (Subscriber or Customer)
Gender (only available for NYC and Chicago)
Birth Year (only available for NYC and Chicago)

# Questions Answered
The Python script in this project calculates a variety of descriptive statistics for each city, including:

1. Popular times of travel:
   * Most common month
   * Most common day of week
   * Most common hour of day
2. Popular stations and trip:
   * Most common start station
   * Most common end station
   * Most common trip from start to end (i.e., most frequent combination of start station and end station)
3. Trip duration:
   * Total travel time
   * Average travel time
4. User info:
   * Counts of each user type
   * Counts of each gender (only available for NYC and Chicago)
   * Earliest, most recent, and most common year of birth (only available for NYC and Chicago)

# Files
The project includes the following files:
  * bikeshare.py: Python script to analyze the bikeshare data
  * chicago.csv: Dataset for Chicago
  * new_york_city.csv: Dataset for New York City
  * washington.csv: Dataset for Washington, DC

# Usage

To run the Python script and generate the statistics for a city, use the following command in the terminal:
python bikeshare.py city

Replace city with chicago, new_york_city, or washington to generate the statistics for the corresponding city. The script will prompt the user to specify filters for the data, such as month or day of week, before calculating the statistics.

# Credits
This project was completed as part of the Udacity Data Analyst Nanodegree program. The data was provided by Motivate.
