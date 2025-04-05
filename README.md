# Telecom Customer Churn Analysis

# Overview
This project involved analysing telecom customer profile data for a particular quarter to examine factors affecting customer churn and provide insights or recommendations back to management to limit further churn.

# Description of Content
I decided to split customers based on newly joined customers this quarter, and those which have joined previously. The goal was to assess to see if there were common characteristics associated with churning customers, and then try to apply that criteria to new customers to predict the risk of churn in new customers.

# Normalization
The key here was creating normalised value factors and churn risk factors, to look at high and low value customers and high and low churn risk customers.

The normalised value factor looked at how "high value" the customer was by applying a ratio of the charges, tenure and referrals. So, a long term customer with high monthly charges and multiple referrals would achieve a higher score.

The normalised churn factor was a little more tricky, and my attempt at a rudimentary naive bayes. This examined the variance from the average churn rate for each characteristic, summed the variances, and then normalised the value. This allowed the creation of the scatterplot profile showing the prevalence of churned customers with low risk factor ratings.

# Analysis
<img width="590" alt="image" src="https://github.com/user-attachments/assets/3e638b8e-46d4-4c63-a43f-087bf82430d3" />

<img width="593" alt="image" src="https://github.com/user-attachments/assets/0ea77868-dbca-4ec2-89e1-8e5a42c3dec2" />

# Recommendations
<img width="604" alt="image" src="https://github.com/user-attachments/assets/a53ecfd8-6df7-4bae-acf9-021f556ef3c9" />



