# 🧴eBay Perfume Market Analysis Dashboard

---


Overview

This project analyzes an e-commerce perfume dataset collected from eBay and published on Kaggle.
The goal is to clean, analyze, and visualize the data to extract business and market insights about:

Market structure

Customer behavior

Pricing strategy

Geographical demand



---




###📂 Repository Structure


📦 eBay-Perfume-Market-Analysis/

├── ebay_dataset/        # Raw & cleaned datasets
│   


├── ebay_python/   # Python scripts & Jupyter notebooks
│   


├── ebay_power bi /     # Power BI dashboard files (.pbix)
│  


├── ebay_images/      # Dashboard screenshots & exported visuals
│  


└── README.md    # Project documentation




---




### 📊 Dataset Description


Each record includes:

brand → Brand name

title → Product title

type → Perfume type (Eau de Parfum, Eau de Toilette, etc.)

price → Item price

priceWithCurrency → Price with currency

available → Available quantity

availableText → Availability description

sold → Sold quantity

lastUpdated → Last update date

itemLocation → City / Country



---




### ⚠️ Dataset Source

[Perfume E-Commerce Dataset](https://www.kaggle.com/datasets/kanchana1990/perfume-e-commerce-dataset-2024)


---



### 🔍 Project Workflow




### 1️⃣ Data Loading & Merging




Loaded two datasets:

Men's perfumes

Women's perfumes

Merged them into one unified dataset

Created a new column:

1 - target_audience → Men / Women

2 - Sales





### 2️⃣ Data Understanding

Explored:

Data types

Distributions

Missing values

Duplicates

Inconsistent brand names

Invalid prices

Messy location formats






### 3️⃣ Data Cleaning & Preprocessing

Handled:

Missing values

Duplicate records

Inconsistent brand names

Inconsistent perfume types

Text normalization

Price formatting issues

Location cleaning (City / State / Country)

Availability text conversion to numeric values

Outliers and logical errors

This step simulates real-world messy e-commerce data cleaning.




 

###  4️⃣ Power BI Data Modeling

Created many business measures such as:

Number of brands

Number of perfumes

Number of types

Average price

Min / Max / Median price

Total sold quantity

Total available quantity

Total sales value

Top selling:

Brand

Perfume

Type

Top countries & cities by:

Sales value

Sold quantity

Optimal price range

Most expensive brand & type


---




### ⚙️ Tools & Technologies

Python: pandas, numpy

Power BI: dashboards , DAX and power query

Jupyter Notebook

GitHub



---



### 📊 Dashboard Pages


#The Power BI dashboard consists of 4 main pages:





### 📈 Market Analysis

Market size overview

Brand distribution

Type distribution

Sales & availability overview





### 👥 Customer Insights

Best selling brands

Best selling perfumes

Sales distribution by ranges

Customer demand patterns




### 💰 Price Optimization

Price distribution

Optimal price range

Most expensive & cheapest brands

Relation between price and sales




### 🌍 Geographical Distribution

Sales by country

Sales by city

Top regions by:

Sold quantity

Revenue



---



### 📸 Dashboard Screenshots


![Market Analysis](https://github.com/ahmed75p/ebay-perfume-market-analysis/blob/main/ebay_images/market%20analysis.png)
![Customer Insights](https://github.com/ahmed75p/ebay-perfume-market-analysis/blob/main/ebay_images/customer%20insights.png)
![Price Optimization](https://github.com/ahmed75p/ebay-perfume-market-analysis/blob/main/ebay_images/price%20optimaization.png)
![Geographical Distribution](https://github.com/ahmed75p/ebay-perfume-market-analysis/blob/main/ebay_images/Geo.png)
![filter](https://github.com/ahmed75p/ebay-perfume-market-analysis/blob/main/ebay_images/filter.png)



---


### 💡 Key Insights


A small number of brands dominate total sales

Most perfumes sell in a specific mid-price range

Some expensive brands sell fewer units but generate high revenue

Certain cities and countries generate much higher demand

Availability does not always mean higher sales



---




###  🚀 Scope of This Project

This project demonstrates:

Real-world data cleaning

Handling inconsistent & messy text data

Exploratory Data Analysis (EDA)

Business-focused Power BI dashboards

End-to-end data analysis workflow



---



### 🔮 Future Work

Sales prediction models

Price optimization machine learning models

Customer segmentation

Demand forecasting by country


---


### 🧑‍💻 Author
**Ahmed Mostafa**  
Data Analyst 
[LinkedIn Profile](https://www.linkedin.com/in/ahmed-mostafa-841412250/)  

📧 Email:
👉 ahmedmostafa75p@gmail.com




