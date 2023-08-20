# Customer Classification Using Power BI DAX and Transform Functions

In this project, we will explore how to perform customer classification using Power BI's Data Analysis Expressions (DAX) language and the Transform Data function. Customer classification is a common task in business analytics where customers are segmented into distinct groups based on various attributes and behaviors. This can help businesses tailor their marketing strategies, optimize customer service, and make informed decisions.

## Table of Contents

- [Introduction](#introduction)
- [Data Preparation](#data-preparation)
- [Customer Segmentation](#customer-segmentation)
- [Conclusion](#conclusion)

## Introduction

Ninja Telecommunications is an Internet Service Provider in Nigeria.<br>
To support their revenue drive and marketing effort, they want to have a better understanding of their customers, especially with regards to how they use their Internet Data Plans.<br>
Ninja Telecoms has over the past 6 months offered different types of Free Internet Data to their customers as incentives based on anything from new signups, data plans, locations and other special promos.<br>
The company would like to be more efficient in their Free Data Offerings and has provided 6 months customer data for profiling before further analysis.<br>

## Data Preparation

1. **Data Import**: Import the customer dataset into Power BI using the Transform Data function. Ensure that the data is properly structured and cleaned, handling missing values and duplicates.

2. **Data Transformation**: Use Power Query Editor to perform necessary data transformations. Merge relevant tables, create calculated columns, and ensure data consistency.

## Customer Segmentation
A customer profiling for further analysis. This profiling should be based on the below rules:

| Assigned Scores | 20 | 15 | 10 |  5 |  1 |
|-----------------|----|----|----|----|----|
| Loyalty         | Purchased Data Every Month                | Purchased Data 5 out of 6 months            | Purchased Data 4 out of 6 months         | Purchased Data less than 4 out of 6 months | Did not purchase data in the 6 months period |
| Bonus Usage     | Did not use bonus at all in 6 months      | Did not use bonus at all in 5 out of 6 months | Did not use bonus at all in 4 out of 6 months | Did not use bonus at all in less than 4 out of 6 months | Used bonus data in all of the 6 months       |



Based on the customers final scores on the above, classify the customers into the following:
 
Tier 1 Priority Service – Above 85% 
Tier 2 Priority Service – Between 75% and 85%
Tier 3 Priority Service + Incentives – Above 60% and Less than 75%
Tier 4 Priority Marketing + Incentives – Less than or equal to 60% 


## Conclusion

This project demonstrates how to use Power BI's DAX language and Transform Data function to perform customer classification based on their purchasing behavior and characteristics. By utilizing these techniques, businesses can gain valuable insights into their customer base and make data-driven decisions to improve their strategies and overall performance.

Feel free to customize the project with your own data and experiment with different segmentation algorithms and visualizations to better suit your business needs. Happy analyzing!
