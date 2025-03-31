# Uncovering the Main Drivers of Luxury Watch Prices
The findings are open to anybody! But those into watch collecting might find it more fascinating.

Watch collecting is one of my main hobbies, so completing this project was very insightful to me and further enhanced my knowledge in horology. 
Since starting watch collecting, I have been aware of the somtimes lucrative price tags on timepieces, and always wondered why some watches
can be twice as expensive as a similar watch. 

# Project Overview
This project analyzes a dataset of watch specifications (brand, model, price, movement type, country of origin, case diameter, crystal material, complications, etc.). The goal is to derive insights about:

* Average price by brand, country of origin, crystal type, and more
* The relationship between watch diameter and price
* The effect of complications (e.g., chronograph, moonphase) on the average price
* Brand vs. model count distribution and average prices

By combining SQL queries and data visualizations, I uncover which factors most influence watch pricing and highlight interesting trends in the luxury watch market.

# Data Overview
The dataset was used from Kaggle (https://www.kaggle.com/datasets/rkiattisak/luxury-watches-price-dataset/code). The data includes multiple primary fields such as
brand, model, movement type, complication, and most importantly, the price in USD. 

# Key Recommendations
1. Swiss Brands Dominate on Price
  * Swiss watchmakers have the highest average price - reflecting the premium associated with Swiss craftsmanship and heritage.
2. Movement & Crystal Material
  * Automatic watches with sapphire crystals generally command higher prices compared to quartz watches with mineral crystals.
3. Complications Correlate With Higher Prices
  * High‐complexity features (tourbillon, perpetual calendar, minute repeater, etc.) significantly raise average prices.
  * If a buyer is looking to spend the least on a luxury watch, look for a GMT (second time zone) watch.
4. Brand Model Count
  * Some brands release many models at varying price points, which can lower their overall average price or create broad brand diversity.
  * High‐end brands often have fewer models, but each priced higher.


# Tools Used
* SQL, PGAdming4, Postgresql, Excel, Tableau
* SQL techniques used - CTEs, basic select and group by functions, aggregate functions

# Challenges
The main challenge of performing analysis on this dataset was data cleaning. In the original dataset from Kaggle, there were n/a values present in the dataset,
so filtering out those was necessary for further analysis. Furthermore, the original dataset uses a comma in the cell for price, so I chose to remove all commas in the 
cleaned version of the dataset.
