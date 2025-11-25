# EDA-on-Car-Dekho
Car Dekho Sales Overviews
CarDekho Used Car Analysis (README Summary)

# Project Overview
This project performs Exploratory Data Analysis (EDA) on used-car listing data from CarDekho. The analysis helps to understand how different factors like car age, brand, fuel type, transmission, and mileage affect the resale price.

# Objectives

Analyze resale price distribution by brand, year, and fuel type

Understand how car age and kilometers driven influence price

Identify popular car brands and their market share

Explore trends in ownership, transmission type, and seller type

# Dataset

Source: CarDekho dataset (CSV)

Key columns :

name – brand + model

year – manufacturing year

selling_price – resale price in INR

km_driven – total kilometers run

fuel – petrol/diesel/CNG/electric

seller_type – individual or dealer

transmission – manual/automatic

owner – number of previous owners

# Tools & Technologies

Python (Pandas, NumPy)

Data Visualization: Matplotlib, Seaborn

Jupyter Notebook for analysis

# Key Findings (example, adjust to your findings)

Petrol cars form the majority of listings

Older cars (e.g., > 10 years) tend to have much lower prices

Automatic transmission cars cost more than manual ones on average

Mileage (km_driven) and car age are strong predictors of resale value

Maruti, Hyundai, and Honda are among the most frequent brands in the dataset

# Visualizations

Bar charts (fuel type, seller type)

Scatter plots (price vs km driven)

Line charts (price trend by manufacturing year)

Pie charts (market share of seller types or brands)

# Instructions to Run

Clone the repository

Install the required Python packages:

pip install -r requirements.txt


Open EDA.ipynb in Jupyter Notebook and run all cells

# Conclusion
This analysis gives valuable insights about the used car market (from CarDekho), helping both buyers and sellers make data-driven decisions about pricing, car selection, and timing.
