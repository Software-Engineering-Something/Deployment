Stock market data is extracted from file for each industry. The stock movement of companies would be compared based on these 6 parameters :- ‘High’, ‘Low’, ‘Open’, ‘Close’, ‘Volume’, ‘Adj Close’.
- ‘High’ :- Highest price during the day.
- ‘Low’ :- Lowest price during the day.
- ‘Open’ :- Opening price of the day.
- ‘Close’ :- Closing price of the day.
- ‘Volume’ :- Total number of shares of stock traded during the day.
- ‘Adj Close’ :- The closing price is amended to account for any corporate actions to give the ‘Adjusted closing’ price.

The step to deploy the project
- Imports & Data through CSV file
The data source we'll be using for the companies with the same industry and we'll read in the data with pandas-datareader.
- Exploratory Data Analysis
Exploratory data analysis is an important step in any machine learning project because the better we understand our data the more effective our methods can be.
- K-Means Clustering
Even though we've just normalized the data, we're going to use normalize again in a pipeline just to see how pipelines work in scikit-learn.
- We are now going to do a linear dimensionality reduction using singular value decomposition of the data.
- We're going to do this to project it to a lower dimensional space so that we can graphically represent the different clusters.
- Summary of Stock Market Clustering with K-Means
