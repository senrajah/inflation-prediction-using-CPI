# inflation-prediction-using-CPI

# Inflation Prediction

#### About
Our project seeks to look at how different global financial and non-financial factors (hereon referred to as "cool factors") drive inflation. For the purpose of our project, inflation shall be quantified by looking at the rise of the Consumer Price Index (CPI) in the USA over the years.

By analysing these factors, we seek to understand inflation from two points of view:
To understand if factors traditionally theorised to have correlations with inflation in traditional economic literature (e.g. crude oil prices, Producer Price Index (PPI)) really do have their theorised correlations with CPI and to quantify the extent of their relationships.


For a detailed walkthrough, please view the source code in order from:
1. [Data Extraction And Cleansing](https://github.com/senrajah/inflation-prediction-using-CPI/blob/main/DataExtractionAndCleansing.ipynb)
2. [Data Visualisation](https://github.com/senrajah/inflation-prediction-using-CPI/blob/main/DataVisualization.ipynb)
3. [Linear Regression](https://github.com/senrajah/inflation-prediction-using-CPI/blob/main/LinearRegression.ipynb)
4. [K-Nearest Neighbours (KNN)](https://github.com/senrajah/inflation-prediction-using-CPI/blob/main/KNN.ipynb)
5. [ARIMA](https://github.com/senrajah/inflation-prediction-using-CPI/blob/main/ARIMA.ipynb)


#### Problem Definition
To address the two areas we set out to explore, there are some important questions which can help us better quantify and structure our analysis:
1. What are the individual relationships between factors in traditional finance and CPI? Which has the highest correlation to CPI?
2. Are there any multivariate relationships between these factors in traditional finance and CPI?
3. Are there any multivariate relationships between both traditional financial factors that could help us better predict CPI?

#### Conclusion
Our best models to predict CPI:
- ARIMA with 5 exogenous factors

There is value in exploring factors not traditionally agreed upon in traditional economic literature for predicting inflation.

#### What did we learn from this project?
Apart from the data extraction, visualisation and regression we learnt in the module, we applied our learning of Linear Regression, KNN and ARIMA, as well as tied together our financial knowledge, throughout this project.

#### References
1. US Consumer Price Index (CPI) dataset: https://www.bls.gov/cpi/data.htm
2. Business Inflation Expectations (BIE) dataset: https://www.atlantafed.org/research/inflationproject/bie.aspx
3. Crude Oil Price dataset: https://tradingeconomics.com/commodity/crude-oil
4. US Producer Price Index (PPI) dataset: https://fred.stlouisfed.org/series/PPIACO
5. US Unemplyment Rate dataset: https://www.kaggle.com/datasets/axeltorbenson/unemployment-data-19482021
6. S&P 500 dataset: https://finance.yahoo.com/quote/%5EGSPC?p=^GSPC&.tsrc=fin-srch
7. Nominal Effective Exchange Rate dataset: https://fred.stlouisfed.org/series/NBUSBIS

