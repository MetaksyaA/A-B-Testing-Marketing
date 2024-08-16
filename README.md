A/B Testing - Marketing
Project Overview
This project analyzes the effectiveness of marketing ads using A/B testing. The dataset provides insights into the behavior of users who were exposed to either advertisements (ads) or public service announcements (PSA). The goal is to determine whether the ads were successful and if the differences between groups were statistically significant.

Dataset Description
The dataset contains the following columns:

Index: Row index
User ID: Unique identifier for each user
Test Group: Indicates whether the user was in the 'ad' group (saw advertisements) or the 'psa' group (saw public service announcements)
Converted: Indicates whether the user purchased the product (True) or not (False)
Total Ads: The total number of ads seen by the user
Most Ads Day: The day when the user saw the highest number of ads
Most Ads Hour: The hour of the day when the user saw the highest number of ads
Key Findings
Group Dominance: The 'ad' group dominated over the 'psa' group.
Conversion Rate: Users who did not purchase the product outnumber those who did.
Statistical Analysis:
Z Test for Proportions: Used to evaluate the statistical significance of the differences between groups.
Independence Test: Analyzed the independence of categorical variables in relation to conversion.
Peak Hours: Identified peak hours and their relationship with conversion metrics.
Ads and Conversion Relationship: Mann-Whitney U Test was applied to assess the relationship between the number of ads seen and the conversion status.
Statistical Methods
Z Test for Proportions: To evaluate the difference in proportions between the 'ad' and 'psa' groups.
Independence Test: To test the independence of categorical variables related to conversion.
Mann-Whitney U Test: Used to evaluate the relationship between the total number of ads and conversion status.
Conclusion
This project offers insights into how different types of media (ads vs. PSAs) impact user behavior and conversion rates. Statistical tests helped determine whether these differences are significant.

Installation and Usage
To run the analysis in this project, clone the repository and execute the Jupyter notebook. You will need the following dependencies:

Python 3.x
Jupyter Notebook
Libraries: pandas, numpy, scipy, matplotlib, seaborn
