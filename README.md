# Analysis of Online Training Program Tokens

## Introduction
This Python script analyzes a dataset of online training program tokens. The dataset contains information about the token, the course, the status of the token, the expiry date of the token, the name and email of the redeemer, the status of the course, and the start date of the course.

## Code Explanation
Here's a step-by-step explanation of the code:

1. Reading the CSV file into a pandas DataFrame df.
2. Creating a new column attempts in the DataFrame based on specific conditions.
3. Creating a Boolean Series is_duplicated for duplicated 'Redeemer Email'.
4. Updating the 'attempts' column for specific conditions.
5. Converting the 'Token Expiry Date' column to datetime format.
6. Creating a new DataFrame in_progress_df with rows where 'Course Status' is 'In Progress'.
7. Counting the number of each value in the 'attempts' column and printing the result.
8. Grouping the DataFrame by 'Token Status' and 'Course Status', calculating the size of each group, resetting the index, and calculating the percentage of each group.
9. Creating a pie chart using Plotly to visualize the distribution of the 'Explanation' column.
10. Repeating the grouping and percentage calculation for 'attempts' equal to 2.
11. Grouping the DataFrame by 'Token Status' and 'Course Status', calculating the size of each group, resetting the index, and calculating the percentage of each group.
12. Creating a pie chart using Plotly to visualize the distribution of the 'Combined Status' column.

## Conclusion
This script provides insights into the online training program tokens dataset by performing various data analysis tasks.
