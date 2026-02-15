# Power-BI-dashboard-creation-using-EA-Stock-Analysis
The analysis demonstrates that EA stock prices contain predictable patterns  useful for financial planning.

-----------------------------------------------------------------------------------
***PROJECT SUMMARY***

The analysis demonstrates that EA stock prices contain predictable patterns 
useful for financial planning. Identifying key price drivers (opening price, 
trading volume, volatility) enables more accurate forecasting and informs 
risk management decisions.

PowerBI/EA_Stock_Analysis_2351s0479.pbix
- Interactive Power BI dashboard.
- Features: KPI cards, price trends chart, volume analysis, 
  volatility gauge, returns distribution, and date slicer.
- Designed for non-technical stakeholders.
- Can be opened in Power BI Desktop or Service.

-----------------------------------------------------------------------------------
***KEY TECHNICAL METRICS***

MODEL PERFORMANCE:-
R² Score (Training): [INSERT VALUE]
R² Score (Testing): [INSERT VALUE]
Root Mean Squared Error: $[INSERT VALUE]
Mean Absolute Error: $[INSERT VALUE]
Mean Absolute Percentage Error: [INSERT VALUE]%

DATA CHARACTERISTICS:-
Total observations: 1,258 trading days
Date range: [START] to [END]
Price range: $[LOW] to $[HIGH]
Average daily volume: [X] shares
Price volatility: [LOW/MEDIUM/HIGH]

PREDICTIONS:-
30-day average forecasted price: $[INSERT VALUE]
Forecast range: $[LOW] to $[HIGH]
Model confidence (R²): [X]% of variance explained

-----------------------------------------------------------------------------------
***HOW TO USE EACH COMPONENT***

FOR REPRODUCING THE ANALYSIS:-
1. Open Code - Google Colab/2351s0479.ipynb in Google Colab
2. Upload EA.csv when prompted
3. Run all cells in order
4. Review output metrics and charts
5. Use results to understand model performance

FOR MAKING BUSINESS DECISIONS:-
1. Open PowerBI/EA_Stock_Analysis_2351s0479.pbix
2. Review current KPI values (Left side cards)
3. Examine the price trends chart
4. Check the volatility gauge for risk assessment
5. Use the date slicer to examine specific periods
6. Export relevant charts for presentations

-----------------------------------------------------------------------------------
***POWER BI DASHBOARD DISCRIPTION***

The designed interactive Power BI dashboard to visualise Electronic Arts stock market data and communicate key insights to business stakeholders. The dashboard serves as a real-time business intelligence tool that transforms complex financial data into accessible visual formats.

Dashboard Structure and Components:-
At the top left, four Key Performance Indicator (KPI) cards display critical. 

metrics at a glance:-
The current stock price is $176.61, with an average daily trading volume of 2.43 million shares, an average daily return is 0.04%, and peak volatility of 0.07. These cards provide executives with immediate insight into EA's current financial position.

The central focal point is a line chart displaying stock price trends with overlaid moving averages. This chart shows the 7-day and 30-day moving averages alongside actual closing prices, enabling viewers to distinguish short-term price volatility from longer-term trends. The moving averages reveal that EA stock has maintained a generally stable trend around $200-205 per share over the analysis period.
The volatility gauge shows current price volatility on a scale, with the orange indicator pointing to 0.01, representing relatively low volatility. The trading volume column chart displays daily volume patterns, revealing which days experienced higher trading activity. The price volatility area chart shows how volatility evolved, showing periods of elevated and reduced price fluctuation.
Finally, a scatter plot shows the distribution of daily returns, enabling analysis of return consistency and outlier days with unusual price movements.
