# Data-Analyst-Portfolio
This is a repository that I have created to showcase skills, share projects and track my progress in Data Analytics / Data Science related topics.


# Project 1: Revenue Measurements ( https://public.tableau.com/app/profile/merve.al.kan/viz/Book1_17257103004620/Dashboard1?publish=yes )
This project showcases a comprehensive revenue measurement dashboard developed on Tableau Public. Designed to be readily accessible for all users, it provides a clear and actionable overview of critical financial metrics, empowering stakeholders with data-driven insights.

## Key Features:

* Extensive KPI Coverage: Tracks essential KPIs like Monthly Recurring Revenue (MRR), Paid Users, Average Revenue Per Paid User (ARPPU), and Churn Rate, enabling comprehensive revenue analysis.
* Granular Filtering: Facilitates insightful analysis by allowing users to filter data by date range, user language, and user age, providing a deeper understanding of revenue trends across different user segments.
* Data-Driven Visualizations: Adheres to best practices in visual design, ensuring charts and graphs are clear, relevant, and consistent, promoting optimal data communication.
* Tableau Public Accessibility: Leveraging Tableau Public allows for easy sharing of the dashboard publicly, enabling wider access and collaboration.

# Project 2 : E-Commerce Sales Analysis (https://github.com/Mervecaliskann/Global_AI_Hub_Veri_Analizi_Bootcamp_Customer-Segmentation)
This Python project analyzes an e-commerce sales dataset to uncover insights into the platform’s sales performance. The primary objective is to clean the data, handle missing values, and create informative visualizations that help identify trends in sales, products, and customer behavior.

## Key Objectives:

* Explore and understand the structure of the e-commerce sales dataset.
* Address missing data issues by using appropriate imputation techniques.
* Perform feature engineering to create new variables that improve analysis.
* Visualize key sales metrics such as top-selling products, customer spending, and sales trends across different countries.

## Methodology:
 
### 1. Data Preparation:

The dataset contains multiple columns including invoice numbers, product descriptions, sales quantities, prices, and customer information. It was first loaded into a Pandas DataFrame. Missing values were identified in several columns such as CustomerID, InvoiceDate, and Description. Approximately 3% of the dataset contained missing values, and a realistic simulation was introduced by randomly removing data across key columns.

### 2. Missing Data Handling: Various techniques were applied to address the missing values:

* Deletion: Rows with excessive missing data were removed to ensure that the analysis was based on complete records.
* Imputation: For smaller amounts of missing data, the missing values were imputed using the following methods:
* Mean/Median Imputation: Numerical columns such as Quantity and UnitPrice were filled using the mean or median values based on the distribution of existing data.
* Forward Fill: For time-related columns like InvoiceDate, forward filling (using the previous value) was applied to handle gaps in time series data.

### 3. Feature Engineering: 

A new feature, Continent, was created by mapping each country to its respective continent. This provided a clearer way to analyze sales trends by region and allowed for more targeted analysis across different geographical areas.

### 4. Visualization: Seaborn and Matplotlib were used to create meaningful visualizations:

* Sales by Country: A bar chart showing total sales across different countries to identify which regions contribute most to revenue.
* Top 10 Best-Selling Products: A bar chart displaying the top-selling products based on quantity sold, providing insights into the most popular items.
* Daily Sales Trend: A time series plot to analyze how sales vary over time, identifying peak sales days and seasonal trends.
* Customer Spending: A scatter plot and summary statistics were generated to identify high-value customers and their spending patterns.

## Key Findings:

* Customer Behavior: A significant proportion of transactions were made by customers from the United Kingdom, which led to the country being the highest contributor to total sales.
* Top Products: A handful of low-cost and high-frequency products dominated sales figures.
* Sales Patterns: There were noticeable spikes in sales on certain days, indicating possible promotional activities or seasonal effects.
* Customer Spending: The analysis revealed a strong correlation between customer loyalty and high spending, with a few customers contributing the majority of revenue.

### Kaggle Link: https://www.kaggle.com/code/mervcaliskaan/globalaihubveri-analizi-bootcamp-customeranalysis

# Project 3: Jobs in Data Analysis (https://github.com/Mervecaliskann/Jobs-in-Data-Analysis)

This Python project explores the Jobs in Data dataset, focusing on job roles and their characteristics. The project includes a unique challenge: introducing random missing values to the dataset to simulate real-world scenarios and demonstrate effective handling techniques.


## Key Objectives:

* Analyze job roles and their features.
* Simulate random missing data and address its impact.
* Create insightful visualizations for trends and patterns.

## Methodology:

*Data Preparation:
Loaded the dataset and introduced random missing values (~3% of the data).
Ensured the missing values were distributed across key columns for realistic complexity.

*Missing Data Handling:
Used techniques such as mean, median, and mode imputation to address missing values.
Evaluated the impact of different imputation methods on the dataset.

*Visualization:
Generated visualizations using Seaborn and Matplotlib to analyze job role distributions and relationships between features.

## Key Techniques and Tools:

* Random missing data simulation and imputation techniques.
* Data cleaning and preprocessing with pandas.
* Visualizations using Seaborn and Matplotlib.

# Project 4: Cohort Analysis and Revenue Metrics for SaaS Company  ( https://public.tableau.com/app/profile/merve.al.kan/viz/GoIT-Homework2-Merve/ODEV4-Dashboard2?publish=yes )
This project showcases a comprehensive revenue measurement dashboard developed on Tableau Public. It provides a clear and actionable overview of critical financial metrics, empowering stakeholders with data-driven insights.

## Enhanced Functionality:

This iteration expands upon the previous version by introducing several new features:

* Calculated Metrics: Worksheets were created to calculate metrics like New Monthly Recurring Revenue (MRR) and total revenue growth over time, providing more granular insights into revenue trends.
* Cohort Analysis: A cohort analysis was conducted to examine the revenue generated by customers who subscribed in different months. This deepens understanding of customer lifecycle and subscription patterns.
* Enhanced Data Exploration:
A graph illustrating total revenue and its percentage change over time was incorporated for a clear visual representation of revenue growth.
Location and time filters were added to enable dynamic exploration of revenue data by different customer segments and time periods.
* Heatmap Visualization: A color-coded heatmap depicts the revenue contribution of each customer cohort over time, visually highlighting high-performing cohorts.
* Cohesive Dashboard Design: All worksheets have been integrated into a single, user-friendly dashboard for a comprehensive view of the company's financial performance.


# Project 5:  Analyzing User Journeys in E-Commerce (BigQuery & Google Analytics 4)  ( https://console.cloud.google.com/bigquery?sq=585628036168:d6e02c9772a5487dbbdf898b8a14c381 ) & ( https://console.cloud.google.com/bigquery?sq=585628036168:27d0616e68a3497eae44533f3091cc77 )

This project explores user behavior within a sample e-commerce dataset for January 2021, leveraging Google Analytics 4 and BigQuery. By focusing on key conversion points like sessions, add-to-cart actions, checkout initiations, and purchases, we calculated conversion rates and gained insights into user journeys.

## Technical Skills Highlighted:

* BigQuery: Utilized BigQuery's powerful querying capabilities to analyze the sample e-commerce data.
* Data Analysis: Employed analytical techniques to calculate conversion rates and identify trends in user behavior.
* Google Analytics 4 (GA4) Understanding: Demonstrated proficiency in using GA4 data for user journey analysis.

## Project Benefits:

This project provides valuable insights into:

* Conversion funnel performance: By calculating conversion rates at different stages, we can identify areas for improvement in the user journey.
* User behavior patterns: Analyzing user journeys can help tailor marketing strategies and website design for optimal user engagement.
* Customer acquisition and retention: Understanding user behavior is crucial for customer acquisition and retention strategies.


# Project 6: Calculating Potential Customer Yield with Rule-Based Classification (https://github.com/Mervecaliskann/Calculating-Potential-Customer-Yield-with-Rule-Based-Classification)

This project involved an in-depth analysis of sales data for Gezinomi, a travel industry company. The objective was to estimate potential customer revenue and inform marketing strategies.

## Key Tasks:

* Data Exploration: Uncovered unique cities and Concepts (travel packages or experiences) offered by Gezinomi.
* Revenue Analysis: Calculated total revenue generated from sales.
* Data Transformation: Transformed variables to gain deeper insights into customer behavior and spending patterns.
* Customer Segmentation: Segmented customers based on their spending habits, enabling targeted marketing strategies.

## Benefits for Gezinomi:

This analysis empowers Gezinomi to:

* Optimize Marketing Strategies: Identify the most profitable customer segments and tailor marketing approaches accordingly.
* Enhance Decision-Making: Gain data-driven insights to improve revenue forecasting and resource allocation.
* Personalize Customer Experiences: Cater to specific customer preferences based on segmented spending patterns.

## Technical Skills Highlighted:

* Data analysis techniques for exploring and transforming data
* Customer segmentation methods
* Understanding of travel industry data

# Project 7: Handwriting Recognition via Machine Learning ( https://drive.google.com/file/d/1tbmznzXYPx4pdAKBWfzi_o7TKE8yuozq/view )

This project delves into the development of robust algorithms for recognizing handwritten characters using Convolutional Neural Networks (CNNs). The primary objective was to create a model capable of accurately classifying handwritten digits and names.

## Key Achievements:

* High Accuracy on MNIST: The model achieved an impressive accuracy of 99.30% on the widely recognized MNIST dataset, demonstrating its proficiency in classifying handwritten digits.
* Real-world Application: The model was further tested on a dataset containing handwritten names and surnames, achieving an accuracy of 72.63%. This showcases the model's ability to generalize to more complex and real-world scenarios.

## Methodology:

* Convolutional Neural Networks: CNNs were employed as the core architecture for feature extraction and classification due to their exceptional performance in image recognition tasks.
* Data Preprocessing: The datasets were preprocessed to ensure consistency and enhance model performance, including normalization and augmentation techniques.
* Model Training: The model was trained on the preprocessed data using an optimized training procedure, including hyperparameter tuning and regularization techniques.
* Evaluation: The model's performance was evaluated using appropriate metrics such as accuracy, precision, recall, and F1-score.

## Technologies Used:

* Python: The primary programming language for implementing the model.
* TensorFlow/Keras: Deep learning frameworks used for building and training the CNN.
* MNIST Dataset: A benchmark dataset for handwritten digit recognition.
* Custom Dataset: A dataset containing handwritten names and surnames for real-world evaluation.
  
# Project 8: User Engagement Analysis ( https://docs.google.com/spreadsheets/d/1PnlgDO1HJR2I5KB8FG9Ynjht6k-C6VQm4zp2xVnh4hQ/edit?gid=0#gid=0 )

This project aims to analyze user engagement metrics for a specific product. It involves calculating key metrics such as Daily Active Users (DAU), Weekly Active Users (WAU), and user retention.

## Key steps:

* Data Preparation: Importing the dataset to Google Sheets and calculating basic statistics for user age.
* DAU Calculation: Calculating the number of unique users who used the product on each day.
* WAU Calculation: Calculating the number of unique users who used the product in each week and the average DAU for each week.
* User Retention: Calculating the ratio of average DAU to WAU to measure user stickiness.

## Tools used: 

*Google Sheets, COUNTUNIQUEIFS, SUMIF, COUNTIF, and other statistical functions.

# Project 9: User Engagement Forecasting and Visualization ( https://docs.google.com/spreadsheets/d/1JbRYaAidpETIV5PhzAvBucw9JAoI5uguC9b12alpt_M/edit?gid=1323024643#gid=1323024643 )

This project focuses on predicting and visualizing user engagement metrics. By leveraging linear regression and data visualization techniques, we aim to forecast future Daily Active Users (DAU) and Weekly Active Users (WAU) and gain insights into user behavior.

## Key Objectives:

* Forecasting: Utilize linear regression to predict future DAU and WAU values.
* Visualization: Create informative visualizations to understand trends and patterns in user engagement.
* Data-Driven Insights: Extract meaningful insights from the data to inform product decisions.
  
## Methodology:

* Data Preparation: Prepared the dataset from the previous assignment.
* Linear Regression: Applied linear regression to forecast DAU and WAU for future weeks.
* Data Visualization: Created various charts using Google Sheets, including bar charts, pie charts, line charts, and polynomial trendlines.
* Analysis: Analyzed the visualizations to identify trends and patterns in user behavior.

## Tools Used:

* Google Sheets
* Linear Regression
* Data Visualization

# Project 10: Cohort Analysis of User Retention (https://docs.google.com/spreadsheets/d/12uhgrJ0tY5LDsYD9GqRA_mC8_uTSSjstEsvqOx14VQY/edit?gid=1387101163#gid=1387101163)

This project aims to perform a cohort analysis of user retention using Google Sheets pivot tables. By grouping users based on their first activity month and tracking their subsequent activities, we can identify trends in user behavior and retention rates.

## Methodology:

* Data Preparation: Prepared the dataset from the previous assignment.
* Pivot Table Creation: Created a pivot table to analyze user cohorts based on their first activity month.
* Retention Rate Calculation: Calculated retention rates for each cohort over time.
* Visualization: Used conditional formatting and slicers to visualize the data effectively.

## Tools Used:

* Google Sheets
* Pivot Tables
* Conditional Formatting

# Project 11 : Combining and Analyzing Ad Campaign Data with SQL (https://github.com/Mervecaliskann/Combining-and-Analyzing-Ad-Campaign-Data)

This SQL project aims to combine data from two ad campaign platforms (Facebook Ads and Google Ads) and perform a comprehensive analysis. Using Common Table Expressions (CTEs), we create a unified dataset and then aggregate metrics by date and media source.

## Key Objectives:

* Combine data from multiple sources.
* Utilize CTEs for better code readability.
* Aggregate metrics to gain insights into campaign performance.

## Methodology:

* Data Integration: Combined data from Facebook Ads and Google Ads using a UNION ALL operation.
* CTE Creation: Created a CTE to encapsulate the combined dataset.
* Aggregation: Grouped the data by date and media source to calculate total spend, impressions, clicks, and conversion value.

## Tools Used:

* SQL

# Project 12: Combining-Facebook-and-Google-Ads-Data with SQL (https://github.com/Mervecaliskann/-Combining-Facebook-and-Google-Ads-Data)

This SQL project demonstrates how to combine data from multiple ad platforms (Facebook and Google Ads) using CTEs and JOIN operations. By merging data from different tables, we can get a comprehensive view of our advertising campaigns.

## Key Objectives:

* Combine data from Facebook Ads and Google Ads.
* Use CTEs for better code readability.
* Aggregate metrics by date, media source, campaign, and ad set.

## Methodology:

* Joining Facebook Tables: Joined Facebook tables using INNER JOINs based on common keys.
* Combining with Google Ads: Combined the joined Facebook data with Google Ads data using UNION ALL.
* Aggregation: Grouped the data by date, media source, campaign, and ad set to calculate key metrics.

## Tools Used:

*SQL

# Project 13: Google Looker Studio Dashboard for Ad Campaign Analysis (https://lookerstudio.google.com/reporting/18debe28-ac13-4552-908e-4f39686b1ef6/page/uwo0D)

This project demonstrates the creation of a data dashboard using Google Looker Studio to analyze ad campaign performance. By connecting to a PostgreSQL database and visualizing key metrics, we gain insights into campaign effectiveness and identify areas for improvement.

## Key Features:

* Data Source: PostgreSQL database
* Metrics: Ad spend, CPC, CPM, CTR, ROMI
* Visualizations: Combined chart, line chart, and table
* Filters: Campaign name and ad date

## Methodology:

* Data Connection: Connected Looker Studio to a PostgreSQL database.
* Data Exploration: Created calculated fields for key metrics.
* Visualization: Built a dashboard with various charts and tables.
* Filtering: Added filters to enable interactive exploration of data.

## Tools Used:

* Google Looker Studio
* PostgreSQL

# Project 14: Extracting-UTM-Parameters-and-Analyzing-Campaign-Performance (https://github.com/Mervecaliskann/Extracting-UTM-Parameters-and-Analyzing-Campaign-Performance)

This SQL project focuses on extracting UTM parameters from ad campaign data and performing detailed analysis. By using regular expressions and conditional statements, we can gain deeper insights into campaign performance based on specific UTM parameters.

## Key Objectives:

* Extract UTM campaign parameters from URL strings.
* Handle NULL values and perform calculations accordingly.
* Analyze campaign performance based on UTM parameters.

## Methodology:

* Data Preparation: Combined data from various ad platforms.
* UTM Extraction: Used regular expressions to extract UTM campaign parameters.
* Metric Calculation: Calculated key metrics like CTR, CPC, and CPM using conditional statements.

## Tools Used:

* SQL (PostgreSQL)
* Regular Expressions

# Project 15: Analyzing Monthly Ad Campaign Performance (https://github.com/Mervecaliskann/Analyzing-Monthly-Ad-Campaign-Performance)

This SQL project analyzes ad campaign performance on a monthly basis. Using window functions, we calculate the percentage change in key metrics from month to month for each campaign.

## Key Objectives:

* Calculate monthly metrics for ad campaigns.
* Analyze month-over-month changes in key metrics.
* Use window functions for time series analysis.

## Methodology:

* Data Preparation: Created a monthly view of the data.
* Window Functions: Used the LAG function to calculate month-over-month changes.
* Metric Calculations: Calculated various metrics, including percentage changes.

## Tools Used:

* SQL (PostgreSQL)
* Window Functions


* Random missing data simulation and imputation techniques.
* Data cleaning and preprocessing with pandas.
* Visualizations using Seaborn and Matplotlib.

# Project 16: Live Detection System using OpenCV and Deep Learning (https://docs.google.com/presentation/d/1pMppOhrCp9uVrEFDUyic88j29DBkWcXS/edit?usp=sharing&ouid=100361181845443227367&rtpof=true&sd=true)
This project develops a live detection system to verify whether a person in a video is alive or not. By utilizing OpenCV for face recognition and deep learning techniques, the system extracts pulse signals using face detection and Region of Interest (ROI) analysis. Additionally, Generative Adversarial Networks (GANs) are employed to detect fake faces in deepfake videos.

## Key Objectives:

Detect faces in real-time video feeds.
Extract pulse signals from facial regions to verify life signs.
Implement GANs to detect fake faces in deepfake videos.

## Methodology:

Face Detection: Applied OpenCV for accurate face recognition and ROI extraction.
Pulse Signal Extraction: Analyzed subtle facial movements to extract pulse signals.
Deepfake Detection: Utilized GANs to distinguish between real and fake faces in videos.

## Tools Used:

Python
OpenCV (for face detection)
TensorFlow/Keras (for deep learning models)
GANs (for fake face detection)
NumPy and Pandas (for data manipulation)

## Key Features:

Real-time live detection based on facial pulse signals.
Fake face detection using advanced GAN techniques.
Video-based analysis for both live verification and deepfake detection.
