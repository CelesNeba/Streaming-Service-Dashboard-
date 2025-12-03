# Streaming service data analysis
### Objective:
A streaming service wants to analyze the performance of its content across different regions and genres. The goal is to understand viewer preferences and content popularity over time. 

# Dataset
<a href="https://github.com/CelesNeba/Data-Analysis-Dashboard/blob/main/streaming-content-library.csv">
  streaming-content-library.csv
</a>
<a href="https://github.com/CelesNeba/Data-Analysis-Dashboard/blob/main/streaming-subscription-data.csv">
  streaming-subscription-data.csv
</a>

<a href="https://github.com/CelesNeba/Data-Analysis-Dashboard/blob/main/user_viewing_data.csv">
  user_viewing_data.csv
</a>

# Things to do

- Python: Clean the datasets by fixing incorrect timestamps and removing duplicates.
- SQL: Set up tables, import the cleaned data, and write queries to analyze genre popularity, top-
watched shows per region, and subscriber retention rates.
- Tableau: Create dashboards to visualize user engagement, genre popularity by region, and
subscription trends over time.

# Phases & Steps:

## Phase 1: Data Cleaning with Python
1. Import datasets using Pandas.
2. Identify and correct invalid timestamps.
3. Remove duplicate content entries.
4. Normalize inconsistent genre labels and region tags.
5. Save cleaned data to new CSV files.

### Cleaned content library 


![Cleaned Content Library Screenshot](https://github.com/CelesNeba/Streaming-Service-Dashboard-/raw/main/Cleaned%20content%20library%20screenshot.JPG)



### Clean subscription data



![Subscription Data Screenshot](https://github.com/CelesNeba/Streaming-Service-Dashboard-/raw/main/Subscription%20streaming%20data%20screenshot.JPG)



### Clean user viewing data

![Streaming User Viewing Screenshot](https://github.com/CelesNeba/Streaming-Service-Dashboard-/raw/main/Streaming%20user_viewing%20screenshot.JPG)


## Phase 2: SQL Database Integration
1. Set up a database.
2. Create tables for User Viewing Data, Content Library, and Subscription Data.
3. Import cleaned data into the database.
4. Run SQL queries:

o Top-watched genres by region.

o Viewer retention analysis.

o Monthly subscriber growth.


### MYSQL Database and tables creation.

![Screenshot](https://raw.githubusercontent.com/CelesNeba/Streaming-Service-Dashboard-/main/database%20and%20content%20table%20screenshot.JPG)











## Phase 3: Data Visualization with Tableau

1. Connect Tableau to the database.

2. Visualize:

o Viewer engagement across devices.

o Regional genre popularity.

o Subscription trends and churn rates.

o Who cancelled the subscription or expired

# Dashboard   
https://public.tableau.com/app/profile/celes.neba/viz/ContentStreamingAnalysis/Dashboard1

# 📊 Dashboard

Check out the live Tableau dashboard here:  
[View Tableau Dashboard](https://public.tableau.com/app/profile/celes.neba/viz/ContentStreamingAnalysis/Dashboard1)






                                        Dashboard screenshot 




<img src="Dashboard.png" alt="Dashboard Screenshot" width="800">




