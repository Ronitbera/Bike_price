🏍️ Used Bikes Price Analysis
This project analyzes a dataset of used motorcycles listed for sale in India, with the goal of understanding pricing trends based on brand, location, usage, and technical specifications like mileage and power.

📁 Dataset Overview
File: bikes.csv
Columns:

model_name – Name and variant of the bike

model_year – Year of manufacture

kms_driven – Distance the bike has been driven

owner – Ownership history (e.g., first owner)

location – City of the listing

mileage – Claimed mileage of the bike (e.g., 35 kmpl)

power – Engine power of the bike (e.g., 19 bhp)

price – Listing price (in INR)

🎯 Objectives
Understand how pricing varies across different brands and locations.

Examine the influence of bike age, mileage, and power on price.

Prepare the data for further predictive modeling or decision-making.

🔧 Steps Performed
Data Cleaning

Extracted numeric values from textual fields: kms_driven, mileage, and power.

Converted price to numeric values.

Derived a new brand column from the model_name.

Exploratory Data Analysis (EDA)

Brand-wise Pricing: Top 10 brands with the highest average price.

Location-wise Pricing: Cities where bikes are listed at the highest average price.

(Optional) Additional insights into the effects of ownership status and bike age.

Visualization

Bar plots for average prices by brand and location using Seaborn.

📊 Sample Insights
Premium brands like Indian and Moto show higher resale values.

Cities like Maradu and Daman tend to have higher average prices.

Power and mileage figures often correlate with price but also depend on brand reputation.
