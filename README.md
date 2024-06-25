# algotrading
To develop, backtest, and evaluate various algorithmic trading strategies on a diversified portfolio encompassing the entire supply chain from grain production to retail. This includes essential commodities, insurance companies, transportation, and retail/food sectors.
Tickers:

Grain Futures: Wheat (ZW=F), Corn (ZC=F), Soybean (ZS=F)
Insurance Companies: Chubb LTD (CB), The Travelers Companies INC (TRU)
Transportation: Matson INC (MATX)
Retail/Food: Walmart (WMT), Bayer AG (BAYRY)
Strategies Evaluated:

Simple Moving Average (SMA)
Exponential Moving Average (EMA)
Mean-Variance Optimization (Markowitz)
Combined Momentum and Low Volatility
Relative Strength Index (RSI)
Approach:

Data Collection: Gather historical price data for the selected tickers from 2015-01-01 to 2020-01-01 (training period) and from 2022-01-01 to 2024-05-01 (testing period).
Benchmark Strategy: Implement an equal-weighted buy-and-hold strategy for comparison.
Optimization and Backtesting: Develop and backtest each strategy during the training and testing periods, comparing performance metrics such as CAGR, Sharpe ratio, Sortino ratio, and maximum drawdown.
Evaluation: Analyze the results to determine the effectiveness and robustness of each strategy.
Outcome:

Benchmark Performance:

Total Return: 45.60%
CAGR: 8.67%
Daily Sharpe: 0.73
Daily Sortino: 1.21
Max Drawdown: -15.28%
SMA Strategy:

Training Period:
CAGR: 1.88%
Daily Sharpe: 0.26
Daily Sortino: 0.42
Testing Period:
CAGR: 3.89%
Daily Sharpe: 0.41
Daily Sortino: 0.68
EMA Strategy:

Training Period:
CAGR: 1.09%
Daily Sharpe: 0.17
Daily Sortino: 0.28
Testing Period:
CAGR: 1.57%
Daily Sharpe: 0.20
Daily Sortino: 0.33
Markowitz Strategy:

Training Period:
CAGR: 5.04%
Daily Sharpe: 0.45
Daily Sortino: 0.71
Testing Period:
CAGR: -5.62%
Daily Sharpe: -0.25
Daily Sortino: -0.37
Momentum & Low Volatility Strategy:

Training Period:
CAGR: 9.70%
Daily Sharpe: 1.01
Daily Sortino: 1.69
Testing Period:
CAGR: -3.21%
Daily Sharpe: -0.33
Daily Sortino: -0.50
RSI Strategy:

Training Period:
CAGR: 42.35%
Daily Sharpe: 1.76
Daily Sortino: 3.20
Testing Period:
CAGR: -2.41%
Daily Sharpe: 0.03
Daily Sortino: 0.05
Conclusion:
The benchmark strategy showed stable performance, whereas the RSI strategy exhibited the highest returns during the training period but significantly underperformed during the testing period, indicating potential overfitting. SMA and EMA strategies provided modest returns, highlighting the importance of simple yet effective strategies. The Mean-Variance Optimization and Combined Momentum and Low Volatility strategies showed poor performance, suggesting they may not be well-suited for the selected portfolio.

Accomplishment:
Achieved a comprehensive evaluation of multiple algorithmic trading strategies on a diversified supply chain portfolio, providing insights into their performance and robustness under varying market conditions. The findings emphasize the need for cautious application and continuous monitoring of algorithmic strategies to ensure optimal investment outcomes.
