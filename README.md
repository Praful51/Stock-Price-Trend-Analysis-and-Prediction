# Stock-Price-Trend-Analysis-and-Prediction

**Project Overview**

This project focuses on analyzing historical stock price data and building a predictive model to forecast next-day prices. It includes data cleaning, feature engineering, time series analysis, and an interactive Power BI dashboard.

**Tools & Technologies:**

- Python (Pandas, NumPy, Matplotlib, Scikit-learn)
- SQL (for structured analysis)
- Power BI (Dashboard visualization)

**Key Steps Performed:**

- Data Cleaning and Preprocessing
- Feature Engineering (SMA, EMA, Daily Returns)
- Time Series Analysis
- Regression Model for Prediction
- Dashboard Creation in Power BI

**Key Insights:**

**1. Overall Upward Trend**
   
![overall_trend](images/overall_trend.png)

 - The stock shows overall upward trend over time & has shown a remarkable growth overtime with its price moving from nearly 70 to 280 from Year 2020 to 2026

**Recommendation:** AAPL is a strong candidate for long term portfolio holding. Investors who stayed invested through dips were rewarded with nearly 4x return in 6 years. Businesses managing employee pension funds or retail investors should consider AAPL as a core holding rather than a trading stock.

**2. Sustained Bullish Momentum**

![price&ma](images/price_vs_ma.png)
 
- Could be observed that close price is consistently staying above both simple moving averages 20 & 50 throughout indicates a sustained bullish trend
  suggesting that stock has maintained strong upward momentum over 6 years

**Recommendation:**
**3. Volatility**   

![volatility](images/volatility.png)

- Volatility shows a concentrated daily return between -5 % and +5% slightly centered between 0 & 1% suggesting a positive bias,
  Rare extreme events beyond ±10% exist but are very infrequent, suggesting they were driven by 
  specific news or events rather than regular market behavior.  


 **4. EMA- Strong Predictor**

![ema&sma](images/ema_vs_sma.png)
 
-  EMA_20 consistently hugging the Close price more tightly than SMA_20, confirming EMA's faster reaction to price 
movements indicates that it detects the trend shifts earlier.



  

