**Delivery Data Analysis and Prediction Project**

**Project Overview**

This project analyzes and predicts delivery data from an inner-city logistics management system to optimize delivery processes, reduce costs, and improve customer satisfaction. The study uses a real-world dataset from December 2022, containing nearly 100,000 rows and 42 attributes, including order details, driver performance, location data, and shipping costs.

Key Features:

**1. Data Preprocessing**

•	Cleaning: Handled missing values, removed duplicates, and corrected data types for time-related columns.

•	Outlier Removal: Used the Interquartile Range (IQR) method to filter out abnormal delivery times and costs, ensuring more accurate analysis.

**2. Exploratory Data Analysis (EDA)**

•	Time Analysis: Identified peak order times (8 AM – 2 PM) and demand surges during holidays like Christmas and New Year's Eve.

•	Regional Performance: Compared efficiency across regions (HCM1, HCM2, XTRA), finding that HCM2 handles the highest volume while XTRA faces more delivery challenges.

•	Cancellation Analysis: Investigated top reasons for cancellations, such as price concerns and incorrect address entries, and analyzed the financial impact of these cancellations.

•	Logistics Correlation: Explored the relationship between delivery fees, distance, and time across different member ranks (e.g., Platinum vs. Normal).

**3. Predictive Modeling**

•	Order Status Prediction: Implemented a Logistic Regression model to predict whether an order will be "COMPLETED" or "CANCELED".

•	Driver Fee Prediction: Developed a Random Forest Regressor to estimate the total fee paid to drivers based on distance, duration, and surcharges.

•	Model Evaluation: The driver fee model achieved a high performance with an R^2 score of 0.9148.

**Conclusions**

The analysis provides actionable insights, such as identifying high-failure regions and peak-hour traffic patterns, allowing the business to refine shipping policies and driver allocation strategies.
________________________________________
Technologies Used: Python (Pandas, Matplotlib, Seaborn, Scikit-learn).

