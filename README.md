# Project Movie Dashboard
## Table of Content
- [Tools](#tools)

### Project Overview
This data analysis project aims to provide insights into the performance and trends of movies from 2012 to 2016 to the team of creative directors of Apple TV. 
By analyzing various aspects of the movie data, we seek to identify patterns, make data-driven recommendations, and gain a deeper understanding of the industry's dynamics.

### Data Source
Movie Data : The primary dataset used for this analysis is the "Movie Data Homework.xlsx" file, containing detailed information about each movie's performance (box office and budget), actors, directors etc. [Find Original Data Source Here](https://github.com/user-attachments/files/19238827/Dashboard.Excel.xlsx)


### Tools
- Power Query - I used Power Query for Data Cleaning
- Excel - I used Excel for Data Analysis
  - Pivot Tables - for Creating the dashboard and Visualizations
### Data Cleaning and Preparation
- Data loading and inspection.
- Handling errors, missing values.
- Data cleaning and formatting. The excel file after the data cleaning & preparation process can be downloaded here - [Ready to use Dashboard](https://github.com/user-attachments/files/19238692/Dashboard.Excel.xlsx)

### Questions for Data Analysis
1. Which top 10 genres were the most successful (Box) these years?
2. Which top 5 actors were the most successful?
3. Top 5 movies by Box and Budget?
4. Seasonality?...

### Dashboard
![Capture2](https://github.com/user-attachments/assets/33de6483-8e77-40f8-a487-3e0ef4ad0b52)

### Challenges
```
= Table.Group(#"Sorted Rows", {"animal_id"}, 
{{"IndexColumn", each Table.AddIndexColumn(_,"Index",1,1,Int64.Type)}})
```

### Results and Findings
As an example: Best profitable movie was: with Budget of... Box Office Revenue was 102,000,000 USD. The genre of this movie was horror.
![Capture1](https://github.com/user-attachments/assets/426c8cbf-1b7f-4b05-92f9-635f3565ceff)



