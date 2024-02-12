# Data Preparation Phase

## Project Overview

The Waze data team is currently developing a data analytics project aimed at increasing overall growth by preventing monthly user churn on the Waze app. For the purposes of this project, churn quantifies the number of users who have uninstalled the Waze app or stopped using the app. 

## Project background

Waze’s data team is in the earliest stages of the churn project. The following tasks are needed before the team can begin the data analysis process:

- Build a dataframe for the churn dataset

- Examine data type of each column

- Gather descriptive statistics

### Your assignment

You will build a dataframe for the churn data. After the dataframe is complete, you will organize the data for the process of exploratory data analysis, and update the team on your progress and insights.

## Methods Used in Project: 

- Built a dataframe
- Each row represents a single observation, and each column represents a single variable
- Collected preliminary statistics
- Analyzed user behavior

## Key Insights

- This dataset contains 82% retained users and 18% churned users.
- The dataset contains 12 unique variables with types including objects, floats, and integers; the label column is missing 700 values with no indication that the omissions are non-random.
- Churned users averaged ~3 more drives in the last month than retained users.
- Retained users used the app on over twice as many days as churned users in the last month.
- The median churned user drove ~200 more kilometers and 2.5 more hours during the last month than the median retained user.
- Churned users had more drives in fewer days, and their trips were farther and longer in duration. Perhaps this is suggestive of a user profile; our team will have to continue exploring! 
- The median user who churned drove 698 kilometers each day they drove last month, which is about 240% the per-drive-day distance of retained users.
- Regardless of user churn, the users represented in this data drive a lot! It is probably safe to assume that this data does not represent typical drivers at large. 
