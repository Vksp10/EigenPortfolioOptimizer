# Nifty 50 Stock Data Analysis
This project focuses on optimizing a stock portfolio using Principal Component Analysis (PCA) and Eigenvalue decomposition. By analyzing historical data from selected Nifty 50 companies, the project aims to identify the most impactful components that influence stock performance and make informed investment decisions.

# Key Features:
* Data Collection: The stock data is fetched using the yfinance library, covering a period from April 2014 to April 2024.
* Exploratory Data Analysis (EDA): Includes statistical summary, correlation analysis, and visualization of stock data.
* Correlation Heatmap: A Pearson correlation matrix is computed and visualized to identify relationships between the closing prices of different stocks.
* Principal Component Analysis (PCA): PCA is applied to reduce the dimensionality of the stock data, helping to identify patterns and simplify the complexity of the dataset.
* Eigenvalues for Portfolio Optimization: Eigenvalues derived from PCA are used to optimize the stock portfolio by identifying the most influential components, enabling better investment decisions.
* Data Handling: Missing values and data types are checked and addressed as part of the EDA process.
# Tools & Libraries:
* Python: Primary language for data analysis and visualization.
* pandas & numpy: For data manipulation and numerical computations.
* yfinance: To download historical market data.
* seaborn & matplotlib: For data visualization.
* statsmodels: For statistical analysis.
* scikit-learn: For implementing PCA, eigenvalue calculation, and other machine learning techniques.


This project provides insights into the historical performance and relationships between some of the most prominent companies in the Indian stock market, while leveraging PCA and eigenvalues to optimize the stock portfolio by focusing on the most impactful components.
