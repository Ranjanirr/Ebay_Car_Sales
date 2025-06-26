# EBay Car Sales Analysis
-The data folder contains a list of car sales on Ebay. Given this data, I wanted to find how different metrics relate to car price, such as brand, horsepower and registration year
-This analysis was mostly done with cleaning methods, summary statistics, scatter and bar charts


## 📂 Repository Contents

- `Carsales.ipynb` - Main Jupyter Notebook with code and analysis.
- `data/` - autos.csv = https://www.kaggle.com/datasets/sijovm/used-cars-data-from-ebay-kleinanzeigen
- 
## Main Insights

- We have found outliers for extremely expensive cars that skewed the mean. In order to resolve this, we eliminated the top 1 percent of cars which cut the mean in almost half
- We found horsepower to have a positive relation with price, odometer with no correlation with price, and price to vary by registration year from 1950 to 2016
