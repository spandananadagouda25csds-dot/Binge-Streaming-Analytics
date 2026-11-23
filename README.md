BingePlay – Streaming Analytics

Project Overview

BingePlay Streaming Analytics is an SQL-based data analytics project that explores user behaviour, subscription revenue, streaming activity, content ratings and customer churn patterns on a fictional streaming platform.

The project uses SQL queries to extract meaningful insights and support data-driven business decisions.

Objectives

* Analyze active subscriptions and monthly revenue.
* Identify monthly user signup trends.
* Understand viewing behaviour across devices.
* Analyze content ratings and audience preferences.
* Compare original and acquired content.
* Identify binge-watching behaviour.
* Find users who signed up but never watched content.
* Analyze subscription upgrades.
* Detect cliffhanger comeback patterns.
* Measure consecutive-week user engagement.
* Identify potential churn-risk users.

Tools and Technologies

* MySQL / MariaDB
* SQL
* Python
* Google Colab
* Pandas
* SQLAlchemy
* PyMySQL
* GitHub

Database Tables

The project uses five tables:

1. users
2. subscriptions
3. shows
4. watch_sessions
5. ratings

Project Analysis

The project contains 12 SQL analysis questions:

Question	Analysis
Q1	Active Revenue
Q2	Signup Momentum
Q3	Device Analytics
Q4	Rating Distribution
Q5	Originals vs Acquired
Q6	Binge Day Detection
Q7	Q1 Signups Who Never Watched
Q8	Over-Paying Premium/Family Users
Q9	Upgrade Success Cohort
Q10	Cliffhanger Comebacks
Q11	Consecutive-Week Engagement
Q12	Churn Signal Detection

Key Findings

* Active subscriptions generated ₹7,84,260 in monthly revenue as of 30 June 2024.
* May and June recorded the highest signup counts, with 600 signups each.
* Mobile devices recorded the highest number of streaming sessions.
* 71.34% of ratings were 4-star or 5-star.
* Original shows had a higher average IMDb rating than acquired shows.
* 414 binge days were identified during Q2 2024.
* 226 Q1 signups had never watched a session.
* 6 Premium/Family users watched only Basic-tier content.
* 55 users upgraded from Basic to Premium/Family in the January 2024 signup cohort.
* 4,345 cliffhanger comeback events were identified.
* The longest consecutive-week engagement streak was 26 weeks.
* 521 users showed a 50% or greater decrease in watch time in June compared with May 2024.

Repository Contents

* bingeplay_<yourname>.ipynb – Completed notebook containing all 12 SQL queries, outputs and interpretations.
* screenshots/ – Project output screenshots.

How to Run

1. Download or clone this repository.
2. Set up the BingePlay database in MySQL.
3. Open the Jupyter notebook in Google Colab.
4. Install the required Python libraries.
5. Configure the database connection.
6. Run the notebook cells in order to view the SQL queries and their outputs.

Conclusion

This project demonstrates how SQL and Python can be used to analyze streaming-platform data, understand user engagement, evaluate subscription behaviour and identify potential customer churn.

It provides practical experience in SQL querying, data analysis and interpreting business insights.
