Portfolio Optimization Comparative Analysis
This repository contains the code and analysis for an independent study on portfolio optimization techniques. The study compares the performance of different optimization methods, including Modern Portfolio Theory (MPT), Sharpe Ratio maximization, and the Kelly Criterion (Quadratic Utility). The analysis aims to determine which strategy has performed best over the last five years using a set of index ETFs.

Project Overview
The objective of this project is to evaluate the effectiveness of three portfolio optimization strategies and compare their performance against a benchmark:

Modern Portfolio Theory (MPT): Optimizes for maximum return given volatility.
Sharpe Ratio Maximization: Optimizes for the portfolio with the highest risk-adjusted return.
Kelly Criterion: Optimizes for the portfolio that maximizes expected logarithmic utility (Quadratic Utility).
The study uses four widely popular index ETFs as assets: Russell 2000 (IWM), Dow Jones (DJI), NASDAQ (QQQ), and S&P 500 (VOO). The results are compared against an equally-weighted portfolio and the S&P 500 as benchmarks.

Key Components
Data: Historical data for the ETFs from 2014 to 2018 is used for training, and data from 2019 to 2023 is used for testing.
Libraries Used:
empyrial
Riskfolio-Lib
Quantstats
pypfopt
yfinance
matplotlib
Metrics and Analysis:
Return on portfolios
Risk (volatility, drawdown)
Risk-adjusted returns (Sharpe, Sortino, Omega ratios)
How to Run
Prerequisites
Make sure you have the following libraries installed:

bash
Copy code
pip install empyrial Riskfolio-Lib quantstats yfinance matplotlib
Running the Analysis
Clone the repository:
bash
Copy code
git clone https://github.com/your-username/portfolio-optimization-analysis.git
cd portfolio-optimization-analysis
Execute the Jupyter notebook Independent Study(Spring 2024).ipynb to retrieve data, optimize portfolios, and generate reports.

Reports will be generated in HTML format (EqualWeight.html, Sharpe_Portfolio.html, Efficient_Portfolio.html, Max_Quad_Utility.html), providing a detailed breakdown of portfolio performance compared to benchmarks.

Files
Independent Study(Spring 2024).ipynb: The main Jupyter notebook for the analysis.
EqualWeight.html: Performance report of the equally weighted portfolio.
Sharpe_Portfolio.html: Performance report of the Sharpe ratio maximized portfolio.
Efficient_Portfolio.html: Performance report of the efficient frontier portfolio.
Max_Quad_Utility.html: Performance report of the max quadratic utility portfolio.
Proposal Independent Study.pdf: A PDF outlining the project proposal and methodology.
Results
The study will provide insight into:

How well Modern Portfolio Theory, Sharpe Ratio, and Kelly Criterion portfolios perform compared to a simple equally-weighted portfolio and the S&P 500.
The benefits and drawbacks of each optimization method in terms of returns, volatility, and risk-adjusted performance.
Conclusion
This project demonstrates the application of various optimization techniques on portfolio management and the real-world implications of different strategies.

License
This project is licensed under the MIT License - see the LICENSE file for details.

