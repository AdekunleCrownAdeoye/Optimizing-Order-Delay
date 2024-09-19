# Optimizing Order Delay

## Table of Content

- [Project Overview](#project-overview)
- [Data Source](#data-source)
- [Tools](#tools)
- [Data Cleaning and Preparation](#data-cleaning-and-preparation)
- [Data Analysis](#data-analysis)
- [Result and Findings](#result-and-findings)
- [Recommendations](#recommendations)
- [Limitations](#limitations)

### Project Overview
---

- A data analysis project utilizing Excel identified a significant order backlog and delivery delays impacting customer satisfaction. The analysis revealed that driver performance, route characteristics, and vehicle type contribute to these delays.

![Dashboard](https://github.com/user-attachments/assets/35cfb1c4-6607-4692-93fb-e36995e1ddb1)


### Data Source
---

- Excel Spreadsheet: The primary data source, containing information on orders, delivery times, driver performance, route details, and vehicle types.

### Tools
---

- Excel | data analysis, visualization, and calculations.

### Data Cleaning and Preparation
---

In the initial data preparation phase, I performed the following tasks:
1. Data Validation: I ensure data accuracy and consistency by checking for missing values, duplicates, and errors.
2. Data Formatting: I format data appropriately for analysis, such as converting dates and times to the correct format.
3. Data Transformation: I create new variables or transform existing ones as needed for analysis.

### Data Analysis
---

1. Delivery Time Analysis: Calculate average delivery times, identify delivery delays, and analyze the distribution of delivery times.
2. Driver Performance Analysis: Compare the performance of different drivers based on delivery times, identifying areas for improvement.
3. Route Performance Analysis: Analyze the performance of different routes, identifying routes with consistently longer delivery times.
4. Vehicle Performance Analysis: Compare the performance of different vehicle types, assessing their suitability for different delivery types.
5. Allocation Rule Analysis: Evaluate the effectiveness of different allocation rules and identify potential inefficiencies.

### Result and Findings
---

The analysis results are as follows:
1.	Order Backlog: A significant order backlog exists, with 767 of 1,500 orders currently incomplete. This backlog poses a risk to customer satisfaction and operational efficiency.
2.	Delivery Delays: Average delivery delays of 14.51 minutes, while seemingly minor, contribute to the overall backlog and impact customer experience.
3.	Feedback Correlation: Orders with positive feedback exhibit slightly longer average delays than those with negative feedback. This suggests that factors beyond delivery time influence customer satisfaction.
4.	Driver Performance Variability: Certain drivers (D86, D44, D29) consistently experience higher average delays, indicating potential areas for training, route optimization, or vehicle maintenance.
5.	Route Performance Discrepancies: Routes 3, 1, and 2 consistently demonstrate elevated delay times. Analysis of these routes for potential obstacles, traffic patterns, or distance can inform optimization strategies.
6.	Vehicle Performance Differences: Deliveries using "BikeC" exhibit longer average delays compared to "VanA," likely due to factors such as speed, capacity, or range limitations.
7.	Allocation Rule Impact: Despite the intent of expedited deliveries, orders allocated using "Expedited Rules" have higher average delays than those using "Custom" or "Standard" rules, suggesting potential inefficiencies in the "Expedited Rules" system.


### Recommendations
---

1.	Resource Allocation: To address the backlog and prevent accumulation, consider temporarily or permanently increasing resources.
2.	Driver Performance Enhancement: Implement targeted training, optimized route planning tools, and regular vehicle maintenance for drivers with consistently higher delays.
3.	Route Optimization: Conduct a comprehensive review of routes with elevated delay times, considering factors such as traffic patterns, delivery times, and potential obstacles.
4.	Vehicle Assessment: Evaluate the suitability of "BikeC" for deliveries, particularly for longer routes or bulk deliveries, and consider alternative options if necessary.
5.	Allocation Rule Evaluation: Conduct a thorough review of the "Expedited Rules" allocation system to identify and address factors contributing to increased delays. Consider prioritizing improvements to the seemingly more effective "Custom Rules".
6.	Enhanced Customer Communication: Implement proactive communication strategies to inform customers about order status, expected delays, and potential issues. This can mitigate customer dissatisfaction


### Limitations
---

1. Data Quality: The accuracy and completeness of the data can affect the reliability of the analysis.
2. Data Scope: The analysis is limited to the available data and may not capture all relevant factors influencing delivery performance.
3. Assumptions: Certain assumptions may be made during the analysis, which could impact the results.
4. Correlation vs. Causation: The analysis can identify correlations between variables, but it cannot definitively prove causation.

