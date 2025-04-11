Business Use Cases
Player Performance Analysis: Analyze players' performance across different match formats (Test, ODI, T20).
Team Insights: Compare team performance over time and across match types.
Match Outcomes: Understand win/loss patterns, margin of victories, and trends.
Strategic Decision-Making: Assist analysts, coaches, and management in making informed decisions.
Fan Engagement: Present interactive dashboards for fans to explore match data and statistics.

Approach
Data Scraping Using Selenium


Automate navigation to https://cricsheet.org/matches/.
Matches required(Test, ODI, T20, IPL)
Use Selenium to scrape and download all the JSON files available on the page.
Data Transformation


Parse JSON files using Python’s pandas library.
Create separate DataFrames for Test, ODI, and T20 match types.
Database Management


Create an SQL database (e.g., MySQL or SQLite).
Design separate tables for each match type: test_matches, odi_matches, t20_matches.
Insert cleaned data into respective tables using Python’s SQLAlchemy or database connectors.
SQL Queries for Data Analysis


Write 20 SQL queries to extract insights from the data. Examples include:
Top 10 batsmen by total runs in ODI matches.
Leading wicket-takers in T20 matches.
Team with the highest win percentage in Test cricket.
Total number of centuries across all match types.
Matches with the narrowest margin of victory.

EDA using Python
Create 10 different visualizations using libraries like matplotlib,seaborn,plotly
Add those visualizations and make a presentation
Power BI Dashboard


Connect Power BI to the SQL database.
Create an interactive dashboard to visualize:
Player performance trends (batting, bowling).
Match outcomes by teams.
Win/loss analysis across different formats.
Comparative statistics of teams and players.


Results
Automated scraping of JSON files from Cricsheet.
Structured SQL database with separate tables for Test, ODI, and T20 matches.
SQL queries to analyze player and team performance metrics.
A dynamic Power BI dashboard to present insights visually.
