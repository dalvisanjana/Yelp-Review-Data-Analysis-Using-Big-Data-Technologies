# Yelp-Review-Data-Analysis-Using-Big-Data-Technologies

📌 Project Overview

This project analyzes the Yelp Open Dataset to uncover trends in customer reviews, business performance, and user engagement across multiple locations and categories.
It implements a Big Data analytics pipeline using AWS services, PySpark, and Power BI to process, transform, and visualize insights from millions of records.


🎯 Problem Statement

Analyze the Yelp dataset to identify trends in customer reviews, business performance, and user engagement across locations and categories, aiming to provide actionable insights through data exploration only.


🎯 Objectives
Analyze the distribution of star ratings across businesses and categories.
Track review volume and rating trends over time.
Identify top-performing businesses based on ratings and number of reviews.
Compare customer engagement across different cities and business types.
Explore patterns in review behavior, such as review length and timing.

📂 Dataset Information

Source: Yelp Open Dataset

Files Used:

business.json → Business details (name, location, categories, attributes)
user.json → User profiles and engagement metrics
review.json → Review text, ratings, timestamps
checkin.json → Check-in activity timestamps
tip.json → Short tips and recommendations


🛠️ Tools & Technologies

AWS S3 – Data storage
AWS EMR + PySpark – Distributed processing & transformations
AWS Glue – ETL & Data Catalog
AWS Athena – Serverless SQL querying
Power BI – Interactive dashboards
Jupyter Notebook – EDA and visualization


🔄 Methodology

Data Conversion – Converted JSON datasets to CSV for efficient S3 storage and PySpark compatibility.
Initial EDA – Analyzed schema, nulls, duplicates; selected relevant datasets (user, review, business).
Feature Selection – Chose meaningful columns for analysis.
Data Transformation – Cleaned data, extracted year/month, grouped categories, joined datasets in PySpark.
Master Table Creation – Combined datasets into a single analytics-ready table.
Final EDA – Generated insights on top businesses, active users, sentiment trends.
Visualization – Connected Athena to Power BI for dashboards.
