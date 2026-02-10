# Maximizing-Driver-Revenue-using-Hypothesis-Testing
This project applies statistical hypothesis testing to analyze whether payment method (Card vs Cash) has a significant impact on taxi trip fare amounts. Using real-world trip-level data, the analysis combines exploratory data analysis (EDA), data cleaning, and a Welch’s two-sample t-test to derive actionable business insights.

Business Problem -
Do card-based payments generate higher average trip fares compared to cash payments?

Understanding this helps:

Drivers maximize earnings

Platforms promote optimal payment methods

Businesses design data-driven incentives

📂 Dataset Description
The dataset contains individual taxi trip records with the following key fields:

payment_type – Payment method (Card, Cash, others)

fare_amount – Fare charged for the trip

passenger_count – Number of passengers

trip_distance – Distance traveled

Pickup & drop-off timestamps and locations

Each row represents one trip.

🧹 Data Cleaning & Preparation

Identified mixed encodings in payment_type (strings and numeric values)

Filtered dataset to include only:

Card

Cash

Removed missing values from fare amounts

Preserved raw data for statistical testing while using aggregated data only for visualization

📊 Exploratory Data Analysis

Payment method distribution (Card vs Cash)

Passenger count distribution by payment type

Stacked bar charts to visualize rider behavior

Key observations:

Card payments dominate overall trips

Single-passenger trips are most common across both payment types

🧪 Hypothesis Testing
Hypotheses

Null Hypothesis (H₀):
There is no difference in average fare amounts between Card and Cash payments.

Alternative Hypothesis (H₁):
There is a significant difference in average fare amounts between Card and Cash payments.
