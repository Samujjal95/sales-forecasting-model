# sales-forecasting-model
Derived insights to improve demand-supply alignment and used predictive modeling to  forecast sales for each store over the next 12 weeks.

**Project Overview**
Retail Store Inventory Management
Table of Contents
1.	Purpose
2.	Problem Statement
3.	Solution
4.	Dataset
5.	Features


1.**Purpose**:
This project aims to address the inventory management challenges faced by a retail store with multiple outlets across the country. The goal is to provide insights and forecasts that help align supply with demand.

2.**Problem Statement**:
The retail store is experiencing difficulties in managing inventory across its various outlets, leading to discrepancies between supply and demand. This mismatch results in either overstocking or stockouts, affecting sales and customer satisfaction. The dataset consists of weekly sales data for different outlets, and the task is to analyze this data to generate actionable insights.

3.**Solution**:
Using the provided weekly sales data, this project will employ predictive modeling techniques to forecast sales for each outlet for the next 12 weeks. These forecasts will enable the store to optimize inventory levels, ensuring that each outlet has the right amount of stock to meet customer demand.

4.**Dataset**:
This dataset consists data of a retail store that has multiple outlets across the country. 
The dataset consists of the following columns: ‘Store’, ‘Date’, ‘Weekly_Sales’, ‘Holiday_Flag’, ‘Temperature’, ‘Fuel_Price’, ‘CPI’ (Consumer Price Index), and ‘Unemployment’. 
The shape of the dataset is (6435,8) that is 6435 rows and 8 columns.

5.**Key Features**:
•	Data pre-processing and cleaning
•	Exploratory data analysis to uncover key trends and patterns
•	Single Value Decomposition(SVD)
•	Implementation of The ARIMA (AutoRegressive Integrated Moving Average) model to forecast future sales

6.**Technologies Used**:
•	Python: For data analysis and modeling
•	Pandas: For data manipulation
•	Scikit-learn: For implementing predictive models
•	Matplotlib/Seaborn: For data visualization
•	Jupyter Notebook: For interactive analysis and reporting

7.**Conclusion**:
The Trend component indicates the long-term progression of sales, smoothing out the short-term 
fluctuations.
The Seasonality component captures the regular pattern of variability within the year, which could be 
due to holidays, events, or other cyclical factors.
The forecasts for future sales using the ARIMA model have been generated for both a top-performing 
store (Store 20) and a worst-performing store (Store 33).
The forecast suggests that Store 20's sales will remain relatively stable, with slight fluctuations over the 
next 12 periods (assumed to be weeks).
Similarly, the forecast for Store 33 indicates relatively stable sales with minor variations over the next 12 
periods.

