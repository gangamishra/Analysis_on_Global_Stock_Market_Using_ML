**REGRESSION PROJECT**-
**OBJECTIVE**:“To predict global stock market performance using Machine Learning and identify the best model for forecasting Portfolio open".
**Project Overview**-
Dataset: Daily trading records from multiple global stock exchanges.
Target Variable: PortfolioOpen (value of portfolio at start of trading day).
Features: Stock indices (NIFTY50, S&P 500, FTSE100, Hang Seng), commodity prices (Gold, Brent), cryptocurrency (BTC/INR), bond yields, and currency exchange rates (USD/INR, GBP/INR).
**Objective**:
Clean and preprocess raw stock data
Explore correlations and insights using EDA
Apply different ML models to predict PortfolioOpen
Identify the best performing model
**DATA**:
1)PortfolioOpen -The total value of your investment portfolio of the start of trading day.
2)PreviousIndiaTradingDate-The date of last trading session in indian markets.
3)PreviousPortfolioClose-The total values of your portfolio at the end of last trading session.
4)PreviousNIFTY50Close-The closing value of NIFTY 50 index on previous trading day.
5)PreviousUKTradingDate-The date of last uK trading session.
6)PreviousFTSE100Close-The previous day’s closing value of FTSE 100 index.
7)PreviousUSTradingDate-The last Us trading day.
8)PreviousSNP500Close-The S&P 500 index closing value on p;revious US trading day.
9)HongKongTradingDate-The date of current or last trading session in hong kong market.
10)HANGSENOpen-The opening value of Hang Seng index.
11)BRENTClose-The last closing price of BRENT crude oil.
12)GOLDClose-The last closing price of gold.
13)BTCINR-Bitcoin price in indian Rupees.
14)PreviousUS5yrBondYieldClose-The yield on US 5-year government bonds at the previous close.
15)PreviousIndia5yrBondYieldClose-The yield on Indian5-year government bonds at the previous close.
16)USDINRLastClose-Last recorded exchange rate for US Dollar to Indian Rupee.
17)GBPINRLastClose-Last recorded exchange rate for British Pound to Indian Rupee.
**Exploratory Data Analysis (EDA)**:
Line Plots,Scatter Plots,Histograms,Pairplots,Correlation Heatmap.
**Best Model Performance**
The Gradient Boosting Regressor achieved the highest accuracy:
R² Score: 0.9580 (80:20 train-test split)
MAPE: 0.0110
This makes Gradient Boosting Regressor the most suitable model for predicting PortfolioOpen.

