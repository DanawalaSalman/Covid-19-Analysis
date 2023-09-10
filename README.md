# COVID-19 Data Analysis and Visualization

## Project Overview:
This project aims to analyze and visualize COVID-19 data using Python and popular libraries like Pandas and Matplotlib. The project performs the following tasks:

### Cumulative Cases Over Time (Italy, USA, China):
* Reads COVID-19 global data from a CSV file.
* Converts the "Date_reported" column to a datetime object.
* Filters the data for Italy, the United States, and China.
* Groups the data by country and plots the cumulative COVID-19 cases over time for the selected countries.

![alt text](/src/output.png)


### Top 10 Countries with the Highest Cumulative Cases:
* Groups the data by country and calculates the total cumulative cases for each country.
* Selects the top 10 countries with the highest cumulative cases.
* Creates a horizontal bar chart to visualize the top 10 countries.

![alt text](/src/output2.png)


### Daily New Cases Over Time:
* Converts the "Date_reported" column to a datetime object (again).
* Calculates the daily new cases.
* Identifies the date with the most and least daily cases.
* Creates a line plot to visualize daily new cases over time, highlighting the dates with extreme values.

![alt text](/src/output3.png)


## Technical Skills Demonstrated:

* Data cleaning and manipulation using Pandas.
* Data visualization using Matplotlib.
* Handling date-time data.
* Grouping and aggregating data.
* Creating line plots, bar charts, and annotations.
* Data filtering and selection.
