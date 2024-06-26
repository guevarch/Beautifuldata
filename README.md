# Analysis of Online Training Program Tokens

This README.md file provides an analysis of the online training program tokens dataset. The Python script performs various data analysis tasks on the dataset, including creating new columns, updating values based on specific conditions, converting date formats, grouping data, and visualizing distributions using Plotly.

## Findings for 1st Attempts

The analysis reveals the following insights:

| Token Status | Course Status | Count | Percentage | Explanation |
|--------------|---------------|-------|------------|-------------|
| Expired      | -             | 18    | 2.84%      | The token wasn't redeemed and left to expire without being used. |
| Redeemed     | Completed     | 363   | 57.26%     | The student successfully passed the course. |
| Redeemed     | Deactivated   | 2     | 0.32%      | The transaction was reversed or a refund was processed. |
| Redeemed     | Failed        | 64    | 10.09%     | The student failed the course. |
| Redeemed     | In Progress   | 162   | 25.55%     | The course was started but not completed. |
| Redeemed     | Incomplete    | 25    | 3.94%      | The student started but did not complete all assigned modules. |

- The majority of students (57.26% of the total) successfully passed the course.
- A significant portion of students (25.55% of the total) started but did not complete the course. This excludes students that are still currently enrolled.
- A smaller number of students (10.09% of the total) failed the course.
- Some students (3.94% of the total) started but did not complete all assigned modules.
- A very small number of tokens (2.84% of the total) expired without being redeemed or were redeemed but then deactivated.

These findings provide an overview of the outcomes of the first attempt at the course. It is important to note that this analysis is based on the dataset provided and may not represent the entire population of online training program participants.

## Findings for 2nd Attempts

The table below summarizes the status of tokens and courses for the second attempt (attempts == 2):

| Status              | Number of Students | Percentage of Total |
|---------------------|-------------------|---------------------|
| Redeemed - Completed| 36                | 30.25%              |
| Redeemed - Failed   | 83                | 69.75%              |

This summary provides an overview of the outcomes of the second attempt at the course. The majority of students failed the course on their second attempt, while a smaller portion successfully passed the course.

## Findings for Combined Status

The analysis reveals the following insights:

| Token Status | Course Status | Count | Combined Status | Percentage |
|--------------|---------------|-------|-----------------|------------|
| Available    | -             | 2     | Available - -   | 0.248139   |
| Expired      | -             | 18    | Expired - -     | 2.233251   |
| Redeemed     | Completed     | 399   | Redeemed - Completed | 49.503722 |
| Redeemed     | Deactivated   | 2     | Redeemed - Deactivated | 0.248139 |
| Redeemed     | Failed        | 147   | Redeemed - Failed | 18.238213 |
| Redeemed     | In Progress   | 213   | Redeemed - In Progress | 26.426799 |
| Redeemed     | Incomplete    | 25    | Redeemed - Incomplete | 3.101737  |

These findings provide an overview of the combined status of the tokens and courses. The majority of tokens (49.50% of the total) were redeemed and completed successfully. A significant portion of tokens (26.43% of the total) were redeemed and in progress. Some tokens (18.24% of the total) were redeemed but failed, and a small number of tokens (3.10% of the total) were redeemed but incomplete. Additionally, there were a few tokens that were either available (0.25% of the total) or expired (2.23% of the total).

It is important to note that this analysis is based on the dataset provided and may not represent the entire population of online training program participants.