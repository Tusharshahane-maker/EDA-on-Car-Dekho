📊 CarDekho Used Car Data – Exploratory Data Analysis (EDA)

This project performs a detailed Exploratory Data Analysis (EDA) on a used car dataset sourced from CarDekho. The goal is to understand the key factors that influence car resale prices and identify meaningful trends in the Indian used-car market.

📁 Project Overview

Used car prices vary widely depending on multiple factors like brand, manufacturing year, mileage, fuel type, and number of previous owners.
This project analyzes these features to uncover insights such as:

How car age affects resale value

Which brands are most common in listings

Which fuel types dominate the market

How kilometers driven influence price

Price comparison across manual vs automatic transmission

Seller type trends (Dealer vs Individual)

The findings help both buyers and sellers understand the market better.

📌 Dataset Details

Source: CarDekho (public dataset)

Key Columns:

Column Name	Description
name	Car brand & model
year	Manufacturing year
selling_price	Price at which the car is being sold
km_driven	Total kilometers driven
fuel	Type of fuel (Petrol, Diesel, CNG, LPG, Electric)
seller_type	Seller category (Individual/Dealer/Trustmark)
transmission	Manual or Automatic
owner	Number of previous owners
🛠️ Tools & Technologies

Python

Pandas, NumPy

Matplotlib, Seaborn

Jupyter Notebook

🔍 Analysis Performed
✔️ Data Cleaning

Removed missing values

Standardized text fields

Checked for duplicates

Converted data types (numeric, categorical)

✔️ Exploratory Data Analysis

Distribution of selling prices

Price variation by fuel type

Car age vs selling price

Kilometers driven vs price (scatter)

Transmission type comparison

Seller type market share

Top brands in the dataset

Outlier detection with box plots

✔️ Visualizations

Bar charts for brand count, fuel type

Scatter plots (price vs km_driven / year)

Pie charts for seller type distribution

Line charts for price trends by year

Heatmaps for correlation among features

📈 Key Insights

Here are some typical insights (modify based on your notebook results):

Petrol cars dominate the dataset.

Maruti, Hyundai, and Honda are the most listed car brands.

Automatic cars generally have a higher selling price than manual ones.

Cars with lower mileage get better resale prices.

Cars older than 10 years show a sharp decline in value.

Fuel type and transmission strongly influence price.

Owner count impacts buyer perception and reduces price.

▶️ How to Run the Project

Clone this repository:

git clone <your-repo-link>


Install dependencies:

pip install -r requirements.txt


Launch Jupyter Notebook:

jupyter notebook


Open the notebook file:

EDA - Car Dekho.ipynb


Run all cells to reproduce the analysis.
# Conclusion
This analysis gives valuable insights about the used car market (from CarDekho), helping both buyers and sellers make data-driven decisions about pricing, car selection, and timing.
