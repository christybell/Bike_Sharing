# NY Citibike with Tableau

<img src="images/bikesharing-header.png" width="1000" height="300">

## Project Overview
In this module, you'll work with data visualization software called Tableau to present a business proposal for a bike-sharing company. First, you'll learn how to import, style, and portray data accurately. Then, you'll create worksheets, dashboards, and stories to visualize key data from a New York Citi Bike dataset.

## Resources
- **Data Sources**: CSV file for August 2019 data from [NYC Citibike](https://www.citibikenyc.com/system-data) website
- **Software and Tools**: Tableau, Python, Pandas, Jupyter Notebook & Git Bash

## Challenge Deliverables and Results

### Deliverable 1: Change Trip Duration to a Datetime Format
Using Python and Pandas functions, I converted the "tripduration" column from an integer to a datetime datatype to get the time in hours, minutes, and seconds (00:00:00). Then, I exported the DataFrame as a CSV file to use for the trip analysis in Deliverable 2.

<img src="images/Delv 1.PNG">

### Deliverable 2: Create Visualizations for the Trip Analysis
Using Tableau, I created visualizations that show:

- How long bikes are checked out for all riders and genders.
  - I created a line graph displaying the number of bikes checked out by duration for all users, and the graph can be filtered by the hour.
    <img src="images/Delv 2_checkout times.PNG">

  - I created a line graph displaying the number of bikes that are checked out by duration for each gender by the hour, and the graph can be filtered by the hour and gender.
    <img src="images/Delv 2_checkout times by gender.PNG">

- How many trips are taken by the hour for each day of the week, for all riders and genders.
  - I created a heatmap showing the number of bike trips for each hour of each day of the week.
  
    <img src="images/Delv 2_trips by weekday per hour.PNG">
    
  - I created a heatmap showing the number of bike trips by gender for each hour of each day of the week, and the heatmap can be filtered by gender.
  
    <img src="images/Delv 2_trips by gender.PNG">

- A breakdown of what days of the week a user might be more likely to check out a bike, by type of user and gender.
  - I created a heatmap showing the number of bike trips for each type of user and gender for each day of the week, and the heatmap can be filtered by user and gender.

    <img src="images/Delv 2_trips by user type and gender.PNG">

### Deliverable 3: Create a Story and Report for the Final Presentation
For this part of the Challenge, I created a story in Tableau accompanied with this report that describes the key outcomes of the NYC Citibike analysis you did in the module and in Deliverable 2.

<img src="images/Delv 3.PNG">

## Challenge Summary
Provide a high-level summary of the results and two additional visualizations that you would perform with the given dataset.
