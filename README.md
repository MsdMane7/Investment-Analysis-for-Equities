# Investment-Analysis-for-Equities

Overview

This project focuses on analyzing the performance and risk of a portfolio made up of multiple banking stocks. The goal is to understand how the portfolio behaves over time, how risky it is, and how it performs compared to the overall market. The analysis is done using Python and includes key financial concepts such as returns, volatility, risk-adjusted performance, and market sensitivity. The project demonstrates how data science techniques can be applied to real-world financial problems.

Objective:- The main objective of this project is to evaluate a portfolio from both a return and risk perspective. It aims to answer questions such as:
How much return does the portfolio generate?
How risky is the portfolio?
How does it perform compared to the market?
What kind of losses can be expected in worst-case scenarios?
Data Used

The dataset consists of historical stock prices of three major banking stocks along with benchmark market data.
Stock data includes closing prices over a selected time period
Benchmark data represents overall market performance
Data is collected from financial sources and stored in Excel files

Approach
Data Preparation
The data is first cleaned and prepared for analysis. This includes converting date columns into proper format, handling missing values, and ensuring that all stock prices are numeric.

Return Calculation
Daily returns are calculated to understand how stock prices change over time. Both simple returns and log returns are computed to capture different perspectives of price movement.

Portfolio Construction
An equal-weight portfolio is created where each stock contributes equally. The overall portfolio return is calculated by combining individual stock returns based on these weights.

Performance Analysis
The project evaluates how well the portfolio performs by calculating overall returns on a yearly basis. This helps in understanding the growth potential of the investment.

Risk Analysis
Risk is measured using multiple approaches:
Volatility is used to measure how much the portfolio returns fluctuate
Downside risk focuses only on negative returns
Maximum drawdown measures the largest loss from a peak to a low point
Risk-Adjusted Metrics

To understand whether the returns justify the risk taken, several ratios are calculated:

Sharpe Ratio evaluates return relative to total risk
Sortino Ratio focuses on downside risk
Treynor Ratio considers market-related risk
Calmar Ratio compares return with maximum loss

Market Comparison
The portfolio is compared with the benchmark market index to understand its behavior in relation to overall market movements.
Beta measures how sensitive the portfolio is to market changes
Alpha measures the excess return generated beyond what the market explains

Risk Estimation
The project also estimates potential losses using:
Value at Risk, which estimates how much loss can occur at different confidence levels
Conditional Value at Risk, which measures the average loss beyond the worst-case threshold

Key Insights
The portfolio shows stable performance with moderate levels of risk
Risk-adjusted metrics indicate that returns are reasonable compared to the risk taken
The portfolio is less volatile than the overall market
Diversification helps reduce risk, although all stocks belong to the same sector
Downside risk metrics highlight potential losses during unfavorable conditions

Limitations
The portfolio uses equal weights instead of optimized allocation
The analysis is based only on historical data and does not predict future performance
Market conditions are assumed to remain consistent
Risk models used are basic and can be improved
The portfolio includes a limited number of stocks from a single sector
Future Improvements

This project can be enhanced further by:
Applying portfolio optimization techniques to find better asset allocation
Expanding the analysis to include Indian stock market data
Adding machine learning models to predict returns
Incorporing macroeconomic factors such as interest rates and inflation
Building an interactive dashboard for better visualization
Running backtesting strategies to simulate real investment scenarios
Conclusion

This project provides a strong foundation for understanding portfolio analysis using data science. It demonstrates how financial concepts can be implemented using Python to evaluate both performance and risk. The work can be extended into more advanced quantitative finance applications.

Tools and Technologies
Python
Pandas and NumPy for data processing
Matplotlib, Seaborn, and Plotly for visualization
