## 🏍️ BIKE PRICE ANALYSIS

This project analyzes a dataset of used motorcycles listed for sale in India, with the goal of understanding pricing trends based on brand, location, usage, and technical specifications like mileage and power.

## 📁 Dataset Overview

**File:** `bikes.csv`  
**Columns:**
- `model_name` – Name and variant of the bike
- `model_year` – Year of manufacture
- `kms_driven` – Distance the bike has been driven
- `owner` – Ownership history (e.g., first owner)
- `location` – City of the listing
- `mileage` – Claimed mileage of the bike (e.g., 35 kmpl)
- `power` – Engine power of the bike (e.g., 19 bhp)
- `price` – Listing price (in INR)

## 🎯 Objectives

- Understand how pricing varies across different brands and locations.
- Examine the influence of bike age, mileage, and power on price.
- Prepare the data for further predictive modeling or decision-making.

## 🔧 Steps Performed

1. **Data Cleaning**
   - Extracted numeric values from textual fields: `kms_driven`, `mileage`, and `power`.
   - Converted `price` to numeric values.
   - Derived a new `brand` column from the `model_name`.

2. **Exploratory Data Analysis (EDA)**
   - **Brand-wise Pricing:** Top 10 brands with the highest average price.
   - **Location-wise Pricing:** Cities where bikes are listed at the highest average price.

3. **Visualization**
   - Bar plots for average prices by brand and location using Seaborn.

## 📊 Sample Insights

- Premium brands like **Royal Enfield** and **Jawa** show higher resale values.
- Cities like **Bangalore** and **Hyderabad** tend to have higher average prices.
- Power and mileage figures often correlate with price but also depend on brand reputation.

## 📂 How to Run

1. Clone the repository or upload the notebook to [Google Colab](https://colab.research.google.com/).
2. Ensure the `bikes.csv` file is in the working directory.
3. Run the notebook or script to perform analysis and visualize the results.

## 🧠 Future Work

- Build a **machine learning model** to predict prices based on features.
- Cluster similar bikes using **unsupervised learning**.
- Create a **dashboard** for interactive data exploration.

## 📌 Requirements

- Python 3.x
- Pandas
- Matplotlib
- Seaborn
