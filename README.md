# Project Goal
Explore and analyze two datasets (one classification problem and one regression problem) to understand the data and prepare the data ready for the Machine Learning modelling.

# 1. Introduction

We will be discussing the analysis done to two datasets, HR Analytics (hr_data.csv) and Airbnb (listings.csv). We will be extracting data from these two files, exploring them and form prediction problems. Next, we will be wrangling and preparing the data for modelling by performing data cleansing and transformation to categorical and numerical data. Firstly, we will need to have a deeper understanding of the data first.

# 2. HR Analytics (Classification Problem)
HR analytics is revolutionizing the way human resources departments operate, leading to higher efficiency and better results overall. Human resources have been using analytics for years. However, the collection, processing and analysis of data has been largely manual, and given the nature of human resources dynamics and HR KPIs, the approach has been constraining HR.
<b> hr_data.csv </b>

|Variable| Definition|
|---|---|
|employee_id |Unique ID for employee|
|department| Department of employee|
|region| Region of employment (unordered)|
|education| Education Level|
|gender| Gender of Employee|
|recruitment_channel| Channel of recruitment for employee|
|no_of_trainings| no of other trainings completed in previous year on soft skills, technical
skills etc.|
|age| Age of Employee|
|previous_year_rating| Employee Rating for the previous year|
|length_of_service| Length of service in years|
|KPIs_met >80%| if Percent of KPIs(Key performance Indicators) >80% then 1 else 0|
|awards_won?| if awards won during previous year then 1 else 0|
|avg_training_score| Average score in current training evaluations|
|is_promoted| (Target) Recommended for promotion|

HR analytics is revolutionizing the way human resources departments operate, leading tohigher efficiency and better results overall. Human resources have been using analytics foryears. However, the collection, processing and analysis of data has been largely manual, andgiven the nature of human resources dynamics and HR KPIs, the approach has beenconstraining HR. Here is an opportunity to try applying machine learning modelling inidentifying the employees most likely to get promoted.This dataset (hr_data.csv) contains employee personal information, education background,past performance and etc. Detailed information can be found in the below table. You can utilize all these variables to make prediction on whether the employee will be promoted or not. 

# 3. AIRBNB (Regression Problem)
Since 2008, guests and hosts have used Airbnb to expand on traveling possibilities and presentmore unique, personalized way of experiencing the world.This dataset (listings.csv) describes the listing activity and metrics from year 2013 to 2019.

<b> listings.csv </b>

|Variable| Definition|
|---|---|
|id| listing ID|
|name| name of the listing|
|host_id| host ID|
|host_name| name of the host|
|neighbourhood_group| region|
|neighbourhood| sub region|
|latitude| latitude coordinates|
|longitude| longitude coordinates|
|room_type| listing space type|
|minimum_nights| amount of nights minimum|
|number_of_reviews| number of reviews|
|last_review| latest review|
reviews_per_month| number of reviews per month|
|calculated_host_listings_count| amount of listing per host|
|availability_365| number of days when listing is available for booking|
|price (Target)| daily rental price in dollars|

We will utilize the variables provided in the dataset to generate predictions on the rental price of the listed properties. Therefore, this is a regression problem.

Data exploration will be performed first to allow viewers to have a better understanding of the dataset itself, which includes the exploring relations between variables and the target. Hence, we will be producing some visualizations using Jupyter Notebook to help us further understand each data. 
