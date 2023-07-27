
## Sales Data Exploratory Data Analysis (EDA) Project

### Introduction:
This project is an Exploratory Data Analysis (EDA) on a sales dataset spanning from January 2019 to January 2020. The dataset contains information about various sales transactions, including order details, product information, quantities, prices, customer addresses, and cities.

### DataSet Description:
The dataset contains 185686 records, each record representing a unique data. The dataset has various attributes :
Date: The date of the sales transaction. This column records when each purchase occurred.

Order_ID: A unique identifier for each sales order.

Product: The name of the product that was sold. 

Quantity_Ordered: The quantity of the product ordered in each transaction.

Price_Each: The unit price of the product.
Purchase_Address: The address where the purchase was made. 

Hour: The hour of the day when the transaction occurred. 

Total: The total revenue generated from each transaction. 

City: The city where the purchase was made. This column identifies the city associated with each sales transaction.

[DataSet](https://raw.githubusercontent.com/Bytecode-Magnum/Sales_ExploratoryDataAnalysis/main/sales_data.csv)

### Exploratory data analysis: 
In the Exploratory Data Analysis (EDA) of the sales dataset, various operations were performed, including data loading, cleaning, and visualization. Time series analysis was used to identify sales trends over time, while product performance and price analysis helped identify top-selling products and pricing patterns. City-wise analysis was conducted to understand regional variations, and correlation analysis explored relationships between variables and many more.

[Data Processing](https://github.com/Bytecode-Magnum/Sales_ExploratoryDataAnalysis/blob/main/Sales_eda.ipynb)

### Data Visualization:
Data visualization played a crucial role in this project as it helped present complex findings in a more accessible manner. I utilized various visualization techniques, such as bar charts, histograms, scatter plots, and box plots, to showcase different aspects of the data.
Plotly.express is used for data analysis, but github dont render dynamic plots,so below is link for nbviewer. Data visulization

### Libraries:

Here are the Python packages I used for the project: 

[Pandas](https://pandas.pydata.org/)

[Seaborn](https://seaborn.pydata.org/)

[Numpy](https://numpy.org/)

[Plotly express](https://plotly.com/python/)

### Conclusion:
This EDA project aims to provide valuable insights into the sales data, allowing stakeholders to make data-driven decisions for business improvement. Through data exploration and analysis, we hope to uncover patterns, trends, and actionable insights that can lead to increased efficiency, improved marketing strategies, and better customer satisfaction.
