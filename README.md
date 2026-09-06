BUA Foods vs BUA Cement: Investment and Portfolio Analysis

Project Overview

This project is the second report in my A-Z Equity Research Series. It compares BUA Foods Plc and BUA Cement Plc to determine whether investors would have been better off holding BUA Foods, BUA Cement, a combination of both companies, or the Nigerian All-Share Index.

The analysis covers their historical market performance, risk, drawdowns, relationship with the broader market, CAPM-required returns, 2026 performance, financial results, technical structure, Monte Carlo simulations and portfolio application.

One of the most interesting findings from the report is that historical performance did not provide a complete picture of what happened in 2026. BUA Foods produced the stronger historical performance, but BUA Cement became the stronger-performing stock in 2026.

Analysis Period

Historical period: 5 January 2022 to 31 December 2025

2026 review: 1 January 2026 to 31 August 2026

Financial comparison: 2022-2025 annual results and H1 2025 versus H1 2026

Benchmark: Nigerian All-Share Index (ASI)

The historical analysis begins in January 2022 because this was the first period with available BUA Foods market data. The 2026 dataset was kept separate so that current performance could be compared with the companies' historical results.

Project Objective

The analysis was designed to answer four main questions:

Which BUA company produced the stronger historical market performance?

Did that historical advantage continue in 2026?

Do the financial results and technical structures support the performance of each stock?

Can combining both companies produce a better balance between risk and return?

Data Sources

Historical and 2026 share-price data for BUA Foods and BUA Cement were obtained through the Investo.ng API.

Nigerian All-Share Index data were obtained from Investing.com.

Financial-performance figures were obtained from the published financial statements of BUA Foods Plc and BUA Cement Plc.

The price datasets were cleaned and aligned by date before returns, risk measures, correlations and portfolio results were calculated.

Tools and Libraries

The project was completed in Python using:

pandas for data cleaning and analysis

numpy for numerical calculations and simulations

matplotlib and seaborn for charts

mplfinance for candlestick charts and moving averages

scipy for supporting statistical calculations

requests for retrieving market data from the API

Analysis Structure

The notebook follows this order:

Price and market performance

Historical and normalized performance charts

Return and risk analysis

Drawdown analysis

Correlation with the Nigerian All-Share Index

CAPM and systematic risk

2026 performance review

Financial-performance comparison

Technical analysis and moving averages

Monte Carlo simulation

Portfolio application

Investment conclusion

Key Historical Findings

BUA Foods produced the stronger historical market performance. Between 2022 and 2025, the stock generated an annualized return of approximately 78% at about 28% volatility. It recorded a beta of approximately 0.43 and outperformed its CAPM-required return of about 24%.

The business behind the stock also expanded during this period. BUA Foods' revenue increased from ₦418.35 billion in 2022 to ₦1.77 trillion in 2025, while operating margin improved from 27.23% to 36.96%.

BUA Cement followed a less consistent path. Revenue increased from ₦361.00 billion in 2022 to ₦1.18 trillion in 2025, but operating margin fell sharply during the 2023-2024 currency and cost pressures before recovering to 43.60% in 2025. Its net margin also recovered to 30.19% in 2025.

By 2025, both companies had returned to stronger profitability and generated similar levels of free cash flow:

Company

2025 Revenue

Operating Margin

Net Margin

Free Cash Flow

BUA Foods

₦1,774.64bn

36.96%

29.21%

₦381.93bn

BUA Cement

₦1,179.44bn

43.60%

30.19%

₦371.77bn

What Changed in 2026?

The performance ranking changed in 2026. BUA Foods declined by approximately 4.79%, while BUA Cement gained about 73.1% and outperformed the ASI's return of approximately 56.04%.

BUA Cement's stronger return came with considerably higher risk. Its 2026 volatility was approximately 50% and its maximum drawdown was about 40%, compared with volatility of about 28% and a drawdown of approximately 21.3% for BUA Foods. The ASI produced the lowest risk among the three, with volatility of approximately 15.1% and a maximum drawdown of about 11%.

The financial results also showed a clear contrast between both companies.

BUA Foods' revenue declined by 16.15% to ₦765.12 billion, but operating margin increased from 31.22% to 41.89%. Operating cash flow rose to ₦162.18 billion, while lower capital expenditure helped free cash flow increase by 71.87% to ₦146.41 billion. The business therefore became more efficient despite the decline in revenue.

BUA Cement recorded a broader improvement. Revenue increased by 25.60% to ₦728.93 billion, operating margin expanded from 42.29% to 50.93%, and operating cash flow rose by 85.37% to ₦278.45 billion. Free cash flow increased to ₦217.78 billion despite higher capital expenditure.

Technical Analysis

BUA Foods was trading below its 50-day, 100-day and 200-day moving averages after declining from its May 2026 high. This reflected the weaker momentum surrounding the stock, although its historical performance and simulated outcomes suggested the possibility of a recovery.

BUA Cement also experienced a pullback, but its longer-term support structure remained in place, with the price trading above its 200-day moving average.

Monte Carlo Simulation

The Monte Carlo analysis used 10,000 simulations over 252 trading days to estimate a range of possible future prices based on the historical returns and volatility of each stock.

BUA Foods recorded a mean simulated final price of approximately ₦1,466.60 from a last price of ₦760.60, with a simulated probability of profit of approximately 98.67%.

BUA Cement recorded a mean simulated final price of approximately ₦468.34 from a last price of ₦309.00. Its wider range of outcomes reflected the higher volatility of the stock.

The simulation is not a price forecast. It only shows the distribution of outcomes produced when historical return and volatility assumptions are applied repeatedly.

Portfolio Application

The two stocks were combined at different weights to identify allocations for different investment objectives.

Investment Objective

BUA Foods

BUA Cement

Result

Lowest historical risk

60%

40%

Minimum-volatility combination

Best risk-adjusted performance

80%

20%

Highest Sharpe ratio

Highest historical return

100%

0%

Maximum-return allocation

The 80% BUA Foods and 20% BUA Cement portfolio produced the highest historical Sharpe ratio of approximately 1.82. These allocations are results from the historical dataset and are not predictions of how the same portfolios will perform in the future.

Investment Conclusion

BUA Foods had the stronger historical record and achieved higher returns at lower volatility. However, its market performance weakened in 2026 as revenue declined, even though margins and free cash flow improved.

BUA Cement delivered the stronger 2026 performance and recorded a broader improvement across revenue, margins and cash generation. This improvement supported the stock's stronger return, although investors had to accept much higher volatility and drawdown risk.

The analysis shows why historical performance should not be treated as a definite picture of future performance. It can provide useful pointers, but changes in the underlying business, market conditions and risk profile can alter the investment outcome.

Limitations

Historical performance does not guarantee future performance.

Monte Carlo results depend on historical return and volatility assumptions.

The portfolio allocations are based only on BUA Foods and BUA Cement and do not represent a fully diversified portfolio.

Financial results and technical conditions can change after the end of the analysis period.

Differences in available trading dates and market liquidity may affect the calculations.

Full Report

The complete investor-facing report is available on my substack @Lemm Financials.

Author

Olalekan Akinola
Market and Investment Analyst
GitHub | Lemm Financials

Disclaimer

This project is for educational and research purposes only. It does not constitute financial advice or a recommendation to buy or sell any security. Investors should conduct their own research and consider their objectives, risk tolerance and financial circumstances before making investment decisions.
