# Segment - 3

## Responsibility for Third Segment:
The Original CSV file has records around 3 Million and it is decided by team to shorten the file .Python program [clean_Sample](https://github.com/AlyseD/Group_Project/blob/finalcleaning/Clean_Sample.ipynb) to 500 Thousand records. But it also seem too big so again [Shorter Sample](https://github.com/AlyseD/Group_Project/blob/finalcleaning/Smaller_Sample.ipynb) to 100 thousand records. Further this file is edited  for cleanup in [Clean Edited File](https://github.com/AlyseD/Group_Project/blob/finalcleaning/Clean_Edited_Sample.ipynb).
The final CSV is [Final US Accidents](https://github.com/AlyseD/Group_Project/blob/finalcleaning/df_small_sample.csv)

Following cleanup is done
- Removed all Null values
- Deleted Columns which are not required for ML
- Replaced Severity level 1 and 2 to 0and 3 and 4 to 1
- Weather conditions are grouped from 137 to fewer
- Accident time is groued as hour and months



























# Group_Project

Introduction:

The main goal of this project is for our group to collaborate and use the valuable skills we have learned. We will be utilizing remote collaboration, creating a database, cleaning, and extracting the relevant data, using machine learning, and creating a dashboard to display our data. Some of the programs we will be using Postgres SQL, Python, Jupyter Notebook and Tableau during the process. This topic was selected to find patterns in accident occurrence. Using our skills, we can aid in the prediction of an accident, hotspot information, roadway, and weather condition to help avoid fatality accidents.

Analysis:

When do most accidents occur and why? Analyzing accidents can provide valuable information. With this dataset we will be analyzing and answering this question as well as including information about the weather at the time of the accident, accident severity along with longitude and latitude of the accident location. While analyzing this data we can discern accident frequencies and probabilities of accident occurrence.

About the dataset:

This dataset was chosen because it holds information from February 2016 to June, 2020. The dataset includes information on 3.5 million accidents, from 49 states. Weather types and conditions are also available within the dataset.
The dataset we are using is from https://www.kaggle.com/sobhanmoosavi/us-accidents. The sources of information in the dataset API broadcast by law enforcement agencies, traffic sensors, traffic cameras and the US and state departments of transportation.

Communication:

Our group maintains communication through several channels. We utilized Slack, Zoom meetings and class meetings to strategize, prioritize workloads and problem solve together.

Project Outline:

Introduction

A.	Collaborate on project ideas

B.	Select a dataset and programs to build project

C.	When do most accidents occur and Why?

A.	Dataset Information
1.	sources
2.	accessibility
3.  scalability

B.	Machine Learning
1.	model type
2.	test
3.  accuracy

A.	Database
1.	Parsing
2.	Cleaning
B.	Transforming
1.	creating a csv

C.	Postgresql
1.  Queries
2.	Joins

D.	Visualization
1.	Tableau Dashboard

E.  Challenges
1.  changes that we made

Conclusion
A.	Restate Introduction

B.	Summarize findings

C.	Questions

