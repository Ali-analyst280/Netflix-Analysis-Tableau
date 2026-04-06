# Netflix-Analysis-Tableau
This project provides a comprehensive analysis of Netflix's content library using Tablleau. The goal is to uncover trends in content releases, geographical distribution, and popular genres to understand Netflix's global strategy.

The Data Journey (Methodology)
1.	DATA PREPROCESSING (EXCEL)
•	Missing Value Treatment : Identified blank cells in the dataset and filled them with “Unknown” to ensure consistency.
•	Data Deduplication: Removed duplicate records to maintain a unique set of titles.
•	Standardization: Cleaned dand formatted columns for smooth transition to SQL and Tableau.
2.	Data Validation & Refining (SQL)
•	Null Value Removal: Used SQL queries to specify target and remove rows with null values in critical fields, ensuring the data is 100% accurate for visualization.
•	Querying: Verified the distribution of movies and TV shows using structured queries before importing into Tableau.
3.	Data Visualization (Tableau):
•	Developed a comprehensive, interactive dashboard featuring:
o	Release Year Trend: A line/area chart showing Netflix’s growth over time.
o	Content Type Split: A comparison of Movies vs. TV Shows.
o	Geographical Analysis: A bar chart of the Top 10 countries contributing content.
o	Genre & Rating Insights: Breakdown of content by categories and maturity ratings.
Key Insights
•	Peak Period: Content additions spiked significantly between 2016 & 2019.
•	Dominant Markets: The US and India are the primary content hubs for Netflix.
•	Content Strategy: While movies have a higher count, there is a visible upward trend in TV Show productions.
Repository Files
•	Netflix_Data_Analysis_Project.twb : The final Tableau Packaged Workbook.
•	netflix_sql.csv : The final cleaned dataset.
•	Global_Netflix_Library_Insights.png : A visual snapshot of the dashboard.




