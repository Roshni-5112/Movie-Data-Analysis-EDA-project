# Movie-Data-Analysis-EDA-project

Project Overview
This project performs exploratory data analysis (EDA) on IMDb movie data to uncover trends and insights. The analysis primarily focuses on two key questions:

What are the most popular genres of movies over the last five years?
What factors affect movie revenue? Specifically, does a higher budget lead to higher revenue, or do higher-rated movies generate more revenue?

Findings
1. Most Popular Genres Over the Years
The analysis of the last five years revealed the following trends in the most popular movie genres:

2011: Adventure
   
2012: Fantasy

2013: Science Fiction

2014: Adventure 

2015: Western

3. Factors Affecting Revenue
Contrary to common belief, budget and vote scores do not directly affect revenue.
The primary factor influencing revenue is popularity, as observed in the analysis and visualizations.

Limitations
During the analysis, several limitations were encountered:
Missing and Zero Values:
Many columns contained null values and zeros, particularly in revenue-related data.
Rows with zero revenue had to be dropped to ensure meaningful analysis.
Multi-valued Columns:
Columns like "Cast" and "Genres" contained multiple values in a single cell.
These values needed to be split into separate columns for better analysis.

Conclusion
This project provides valuable insights into the trends in movie genres and revenue-driving factors. Future improvements could include handling missing values more effectively and exploring additional factors that impact revenue.

How to Run the Project
Load the dataset.
Clean and preprocess the data.
Perform EDA using visualizations and statistical analysis.
Interpret the results and derive insights.

Technologies Used
Python (Pandas, NumPy, Matplotlib, Seaborn)
