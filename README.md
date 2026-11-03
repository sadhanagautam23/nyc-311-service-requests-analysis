# nyc-311-service-requests-analysis

Overview
This project contains an exploratory data analysis and statistical testing pipeline built around New York City 311 customer service requests. The primary objective is to clean a large-scale municipal dataset, evaluate agency response performance across different complaint categories and boroughs, and apply statistical hypothesis testing to determine whether geographic location and complaint types are statistically dependent.

Project Details & Workflow
- Data Cleaning & Preprocessing: Loaded the raw CSV dataset using Pandas, checked data types, handled missing values, and engineered a custom "Request Closing Time" metric by computing the difference between creation and closure timestamps.
- Exploratory Data Analysis: Generated visual breakdowns including request volumes by the hour of the day, distribution histograms for response times, geographic coordinate mapping for specific parking violations, and comparative bar charts and heatmaps across city boroughs.
- Statistical Hypothesis Testing: Implemented one-way ANOVA testing to evaluate response time variations across complaint types alongside Chi-Square tests of independence to examine relationships between complaint categories and geographic locations.

Tech Stack
- Python
- Pandas & NumPy
- Matplotlib & Seaborn
- SciPy
