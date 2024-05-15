# Awesome Quant Overview

A curated list of insanely awesome libraries, packages and resources for Quants (Quantitative Finance)

[🏠 Home](/README.md) · [🔥 Feed](https://www.trackawesomelist.com/wilsonfreitas/awesome-quant/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung) · [😺 wilsonfreitas/awesome-quant](https://github.com/wilsonfreitas/awesome-quant) · ⭐ 16K · 🏷️ Finance

[ [Daily](/content/wilsonfreitas/awesome-quant/README.md) / [Weekly](/content/wilsonfreitas/awesome-quant/week/README.md) / Overview ]

---

# Awesome Quant

A curated list of insanely awesome libraries, packages and resources for Quants (Quantitative Finance).

[![](https://awesome.re/badge.svg)](https://awesome.re)

## Languages

*   [Python](#python)
*   [R](#r)
*   [Matlab](#matlab)
*   [Julia](#julia)
*   [Java](#java)
*   [JavaScript](#javascript)
*   [Haskell](#haskell)
*   [Scala](#scala)
*   [Ruby](#ruby)
*   [Elixir/Erlang](#elixirerlang)
*   [Golang](#golang)
*   [CPP](#cpp)
*   [CSharp](#csharp)
*   [Rust](#rust)
*   [Frameworks](#frameworks)
*   [Reproducing Works](#reproducing-works)

## Python

### Numerical Libraries & Data Structures

*   [numpy](https://www.numpy.org) - NumPy is the fundamental package for scientific computing with Python.
*   [scipy](https://www.scipy.org) - SciPy (pronounced “Sigh Pie”) is a Python-based ecosystem of open-source software for mathematics, science, and engineering.
*   [pandas](https://pandas.pydata.org) - pandas is an open source, BSD-licensed library providing high-performance, easy-to-use data structures and data analysis tools for the Python programming language.
*   [quantdsl (⭐323)](https://github.com/johnbywater/quantdsl) - Domain specific language for quantitative analytics in finance and trading.
*   [statistics](https://docs.python.org/3/library/statistics.html) - Builtin Python library for all basic statistical calculations.
*   [sympy](https://www.sympy.org/) - SymPy is a Python library for symbolic mathematics.
*   [pymc3](https://docs.pymc.io/) - Probabilistic Programming in Python: Bayesian Modeling and Probabilistic Machine Learning with Theano.
*   [modelx](https://docs.modelx.io/) - Python reimagination of spreadsheets as formula-centric objects that are interoperable with pandas.
*   [ArcticDB (⭐1.1k)](https://github.com/man-group/ArcticDB) - High performance datastore for time series and tick data.

### Financial Instruments and Pricing

*   [OpenBB Terminal (⭐26k)](https://github.com/OpenBB-finance/OpenBBTerminal) - Terminal for investment research for everyone.
*   [PyQL (⭐923)](https://github.com/enthought/pyql) - QuantLib's Python port.
*   [pyfin (⭐303)](https://github.com/opendoor-labs/pyfin) - Basic options pricing in Python. *ARCHIVED*
*   [vollib (⭐630)](https://github.com/vollib/vollib) - vollib is a python library for calculating option prices, implied volatility and greeks.
*   [QuantPy (⭐618)](https://github.com/jsmidt/QuantPy) - A framework for quantitative finance In python.
*   [Finance-Python (⭐693)](https://github.com/alpha-miner/Finance-Python) - Python tools for Finance.
*   [ffn (⭐1.8k)](https://github.com/pmorissette/ffn) - A financial function library for Python.
*   [pynance (⭐294)](https://github.com/GriffinAustin/pynance) - Lightweight Python library for assembling and analyzing financial data.
*   [tia (⭐401)](https://github.com/bpsmith/tia) - Toolkit for integration and analysis.
*   [hasura/base-python-dash](https://platform.hasura.io/hub/projects/hasura/base-python-dash) - Hasura quick start to deploy Dash framework. Written on top of Flask, Plotly.js, and React.js, Dash is ideal for building data visualization apps with highly custom user interfaces in pure Python.
*   [hasura/base-python-bokeh](https://platform.hasura.io/hub/projects/hasura/base-python-bokeh) - Hasura quick start to visualize data with bokeh library.
*   [pysabr (⭐425)](https://github.com/ynouri/pysabr) - SABR model Python implementation.
*   [FinancePy (⭐1.9k)](https://github.com/domokane/FinancePy) - A Python Finance Library that focuses on the pricing and risk-management of Financial Derivatives, including fixed-income, equity, FX and credit derivatives.
*   [gs-quant (⭐2.7k)](https://github.com/goldmansachs/gs-quant) - Python toolkit for quantitative finance
*   [willowtree (⭐220)](https://github.com/federicomariamassari/willowtree) - Robust and flexible Python implementation of the willow tree lattice for derivatives pricing.
*   [financial-engineering (⭐337)](https://github.com/federicomariamassari/financial-engineering) - Applications of Monte Carlo methods to financial engineering projects, in Python.
*   [optlib (⭐381)](https://github.com/dbrojas/optlib) - A library for financial options pricing written in Python.
*   [tf-quant-finance (⭐4.3k)](https://github.com/google/tf-quant-finance) - High-performance TensorFlow library for quantitative finance.
*   [Q-Fin (⭐375)](https://github.com/RomanMichaelPaolucci/Q-Fin) - A Python library for mathematical finance.
*   [Quantsbin (⭐463)](https://github.com/quantsbin/Quantsbin) - Tools for pricing and plotting of vanilla option prices, greeks and various other analysis around them.
*   [finoptions (⭐198)](https://github.com/bbcho/finoptions-dev) - Complete python implementation of R package fOptions with partial implementation of fExoticOptions for pricing various options.
*   [pypme (⭐10)](https://github.com/ymyke/pypme) - PME (Public Market Equivalent) calculation.
*   [AbsBox (⭐25)](https://github.com/yellowbean/AbsBox) - A Python based library to model cashflow for structured product like Asset-backed securities (ABS) and Mortgage-backed securities (MBS).
*   [Intrinsic-Value-Calculator (⭐6)](https://github.com/akashaero/Intrinsic-Value-Calculator) - A Python tool for quick calculations of a stock's fair value using Discounted Cash Flow analysis.
*   [Kelly-Criterion (⭐86)](https://github.com/deltaray-io/kelly-criterion) - Kelly Criterion implemented in Python to size portfolios based on J. L. Kelly Jr's formula.
*   [rateslib (⭐74)](https://github.com/attack68/rateslib) - A fixed income library for pricing bonds and bond futures, and derivatives such as IRS, cross-currency and FX swaps.

### Indicators

*   [pandas\_talib (⭐707)](https://github.com/femtotrader/pandas_talib) - A Python Pandas implementation of technical analysis indicators.
*   [finta (⭐2.1k)](https://github.com/peerchemist/finta) - Common financial technical analysis indicators implemented in Pandas.
*   [Tulipy (⭐89)](https://github.com/cirla/tulipy) - Financial Technical Analysis Indicator Library (Python bindings for [tulipindicators (⭐804)](https://github.com/TulipCharts/tulipindicators))
*   [lppls (⭐327)](https://github.com/Boulder-Investment-Technologies/lppls) - A Python module for fitting the [Log-Periodic Power Law Singularity (LPPLS)](https://en.wikipedia.org/wiki/Didier_Sornette#The_JLS_and_LPPLS_models) model.
*   [talipp (⭐296)](https://github.com/nardew/talipp) - Incremental technical analysis library for Python.
*   [streaming\_indicators (⭐29)](https://github.com/mr-easy/streaming_indicators) - A python library for computing technical analysis indicators on streaming data.

### Trading & Backtesting

*   [skfolio (⭐923)](https://github.com/skfolio/skfolio) - Python library for portfolio optimization built on top of scikit-learn. It provides a unified interface and sklearn compatible tools to build, tune and cross-validate portfolio models.
*   [Investing algorithm framework (⭐72)](https://github.com/coding-kitties/investing-algorithm-framework) - Framework for developing, backtesting, and deploying automated trading algorithms.
*   [QSTrader (⭐2.7k)](https://github.com/mhallsmoore/qstrader) - QSTrader backtesting simulation engine.
*   [Blankly (⭐2k)](https://github.com/Blankly-Finance/Blankly) - Fully integrated backtesting, paper trading, and live deployment.
*   [TA-Lib (⭐9.1k)](https://github.com/mrjbq7/ta-lib) - Python wrapper for TA-Lib (<http://ta-lib.org/>).
*   [zipline (⭐17k)](https://github.com/quantopian/zipline) - Pythonic algorithmic trading library.
*   [QuantSoftware Toolkit (⭐462)](https://github.com/QuantSoftware/QuantSoftwareToolkit) - Python-based open source software framework designed to support portfolio construction and management.
*   [quantitative (⭐57)](https://github.com/jeffrey-liang/quantitative) - Quantitative finance, and backtesting library.
*   [analyzer (⭐206)](https://github.com/llazzaro/analyzer) - Python framework for real-time financial and backtesting trading strategies.
*   [bt (⭐2k)](https://github.com/pmorissette/bt) - Flexible Backtesting for Python.
*   [backtrader (⭐13k)](https://github.com/backtrader/backtrader) - Python Backtesting library for trading strategies.
*   [pythalesians (⭐59)](https://github.com/thalesians/pythalesians) - Python library to backtest trading strategies, plot charts, seamlessly download market data, analyze market patterns etc.
*   [pybacktest (⭐795)](https://github.com/ematvey/pybacktest) - Vectorized backtesting framework in Python / pandas, designed to make your backtesting easier.
*   [pyalgotrade (⭐4.3k)](https://github.com/gbeced/pyalgotrade) - Python Algorithmic Trading Library.
*   [basana (⭐423)](https://github.com/gbeced/basana) - A Python async and event driven framework for algorithmic trading, with a focus on crypto currencies.
*   [tradingWithPython](https://pypi.org/project/tradingWithPython/) - A collection of functions and classes for Quantitative trading.
*   [Pandas TA (⭐4.8k)](https://github.com/twopirllc/pandas-ta) - Pandas TA is an easy to use Python 3 Pandas Extension with 115+ Indicators. Easily build Custom Strategies.
*   [ta (⭐4.1k)](https://github.com/bukosabino/ta) - Technical Analysis Library using Pandas (Python)
*   [algobroker (⭐85)](https://github.com/joequant/algobroker) - This is an execution engine for algo trading.
*   [pysentosa](https://pypi.org/project/pysentosa/) - Python API for sentosa trading system.
*   [finmarketpy (⭐3.4k)](https://github.com/cuemacro/finmarketpy) - Python library for backtesting trading strategies and analyzing financial markets.
*   [binary-martingale (⭐46)](https://github.com/metaperl/binary-martingale) - Computer program to automatically trade binary options martingale style.
*   [fooltrader (⭐1.1k)](https://github.com/foolcage/fooltrader) - the project using big-data technology to provide an uniform way to analyze the whole market.
*   [zvt (⭐3k)](https://github.com/zvtvz/zvt) - the project using sql, pandas to provide an uniform and extendable way to record data, computing factors, select securities, backtesting, realtime trading and it could show all of them in clearly charts in realtime.
*   [pylivetrader (⭐646)](https://github.com/alpacahq/pylivetrader) - zipline-compatible live trading library.
*   [pipeline-live (⭐203)](https://github.com/alpacahq/pipeline-live) - zipline's pipeline capability with IEX for live trading.
*   [zipline-extensions (⭐18)](https://github.com/quantrocket-llc/zipline-extensions) - Zipline extensions and adapters for QuantRocket.
*   [moonshot (⭐192)](https://github.com/quantrocket-llc/moonshot) - Vectorized backtester and trading engine for QuantRocket based on Pandas.
*   [PyPortfolioOpt (⭐4.2k)](https://github.com/robertmartin8/PyPortfolioOpt) - Financial portfolio optimization in python, including classical efficient frontier and advanced methods.
*   [Eiten (⭐2.7k)](https://github.com/tradytics/eiten) - Eiten is an open source toolkit by Tradytics that implements various statistical and algorithmic investing strategies such as Eigen Portfolios, Minimum Variance Portfolios, Maximum Sharpe Ratio Portfolios, and Genetic Algorithms based Portfolios.
*   [riskparity.py (⭐279)](https://github.com/dppalomar/riskparity.py) - fast and scalable design of risk parity portfolios with TensorFlow 2.0
*   [mlfinlab (⭐3.8k)](https://github.com/hudson-and-thames/mlfinlab) - Implementations regarding "Advances in Financial Machine Learning" by Marcos Lopez de Prado. (Feature Engineering, Financial Data Structures, Meta-Labeling)
*   [pyqstrat (⭐349)](https://github.com/abbass2/pyqstrat) - A fast, extensible, transparent python library for backtesting quantitative strategies.
*   [NowTrade (⭐99)](https://github.com/edouardpoitras/NowTrade) - Python library for backtesting technical/mechanical strategies in the stock and currency markets.
*   [pinkfish (⭐260)](https://github.com/fja05680/pinkfish) - A backtester and spreadsheet library for security analysis.
*   [aat (⭐12)](https://github.com/timkpaine/aat) - Async Algorithmic Trading Engine
*   [Backtesting.py](https://kernc.github.io/backtesting.py/) - Backtest trading strategies in Python
*   [catalyst (⭐2.5k)](https://github.com/enigmampc/catalyst) - An Algorithmic Trading Library for Crypto-Assets in Python
*   [quantstats (⭐4.3k)](https://github.com/ranaroussi/quantstats) - Portfolio analytics for quants, written in Python
*   [qtpylib (⭐2.1k)](https://github.com/ranaroussi/qtpylib) - QTPyLib, Pythonic Algorithmic Trading <http://qtpylib.io>
*   [Quantdom (⭐695)](https://github.com/constverum/Quantdom) - Python-based framework for backtesting trading strategies & analyzing financial markets \[GUI :neckbeard:]
*   [freqtrade (⭐26k)](https://github.com/freqtrade/freqtrade) - Free, open source crypto trading bot
*   [algorithmic-trading-with-python (⭐2.4k)](https://github.com/chrisconlan/algorithmic-trading-with-python) - Free `pandas` and `scikit-learn` resources for trading simulation, backtesting, and machine learning on financial data.
*   [DeepDow (⭐848)](https://github.com/jankrepl/deepdow) - Portfolio optimization with deep learning
*   [Qlib (⭐14k)](https://github.com/microsoft/qlib) - An AI-oriented Quantitative Investment Platform by Microsoft. Full ML pipeline of data processing, model training, back-testing; and covers the entire chain of quantitative investment: alpha seeking, risk modeling, portfolio optimization, and order execution.
*   [machine-learning-for-trading (⭐12k)](https://github.com/stefan-jansen/machine-learning-for-trading) - Code and resources for Machine Learning for Algorithmic Trading
*   [AlphaPy (⭐1.1k)](https://github.com/ScottfreeLLC/AlphaPy) - Automated Machine Learning \[AutoML] with Python, scikit-learn, Keras, XGBoost, LightGBM, and CatBoost
*   [jesse (⭐5.3k)](https://github.com/jesse-ai/jesse) - An advanced crypto trading bot written in Python
*   [rqalpha (⭐5.2k)](https://github.com/ricequant/rqalpha) - A extendable, replaceable Python algorithmic backtest && trading framework supporting multiple securities.
*   [FinRL-Library (⭐9.2k)](https://github.com/AI4Finance-LLC/FinRL-Library) - A Deep Reinforcement Learning Library for Automated Trading in Quantitative Finance. NeurIPS 2020.
*   [bulbea (⭐2k)](https://github.com/achillesrasquinha/bulbea) - Deep Learning based Python Library for Stock Market Prediction and Modelling.
*   [ib\_nope (⭐27)](https://github.com/ajhpark/ib_nope) - Automated trading system for NOPE strategy over IBKR TWS.
*   [OctoBot (⭐2.9k)](https://github.com/Drakkar-Software/OctoBot) - Open source cryptocurrency trading bot for high frequency, arbitrage, TA and social trading with an advanced web interface.
*   [bta-lib (⭐440)](https://github.com/mementum/bta-lib) - Technical Analysis library in pandas for backtesting algotrading and quantitative analysis.
*   [Stock-Prediction-Models (⭐7.5k)](https://github.com/huseinzol05/Stock-Prediction-Models) - Gathers machine learning and deep learning models for Stock forecasting including trading bots and simulations.
*   [TuneTA (⭐380)](https://github.com/jmrichardson/tuneta) - TuneTA optimizes technical indicators using a distance correlation measure to a user defined target feature such as next day return.
*   [AutoTrader (⭐862)](https://github.com/kieran-mackle/AutoTrader) - A Python-based development platform for automated trading systems - from backtesting to optimization to livetrading.
*   [fast-trade (⭐340)](https://github.com/jrmeier/fast-trade) - A library built with backtest portability and performance in mind for backtest trading strategies.
*   [qf-lib (⭐475)](https://github.com/quarkfin/qf-lib) - QF-Lib is a Python library that provides high quality tools for quantitative finance.
*   [tda-api (⭐1.3k)](https://github.com/alexgolec/tda-api) - Gather data and trade equities, options, and ETFs via TDAmeritrade.
*   [vectorbt (⭐3.8k)](https://github.com/polakowo/vectorbt) - Find your trading edge, using a powerful toolkit for backtesting, algorithmic trading, and research.
*   [Lean (⭐8.8k)](https://github.com/QuantConnect/Lean) - Lean Algorithmic Trading Engine by QuantConnect (Python, C#).
*   [fast-trade (⭐340)](https://github.com/jrmeier/fast-trade) - Low code backtesting library utilizing pandas and technical analysis indicators.
*   [pysystemtrade (⭐2.4k)](https://github.com/robcarver17/pysystemtrade) - pysystemtrade is the open source version of Robert Carver's backtesting and trading engine that implements systems according to the framework outlined in his book "Systematic Trading", which is further developed on his [blog](https://qoppac.blogspot.com/).
*   [pytrendseries (⭐98)](https://github.com/rafa-rod/pytrendseries) - Detect trend in time series, drawdown, drawdown within a constant look-back window , maximum drawdown, time underwater.
*   [PyLOB (⭐169)](https://github.com/DrAshBooth/PyLOB) - Fully functioning fast Limit Order Book written in Python.
*   [PyBroker (⭐1.6k)](https://github.com/edtechre/pybroker) - Algorithmic Trading with Machine Learning.
*   [OctoBot Script (⭐16)](https://github.com/Drakkar-Software/OctoBot-Script) - A quant framework to create cryptocurrencies strategies - from backtesting to optimization to livetrading.
*   [hftbacktest (⭐1.1k)](https://github.com/nkaz001/hftbacktest) - A high-frequency trading and market-making backtesting tool accounts for limit orders, queue positions, and latencies, utilizing full tick data for trades and order books.
*   [vnpy (⭐24k)](https://github.com/vnpy/vnpy) - VeighNa is a Python-based open source quantitative trading system development framework.
*   [Intelligent Trading Bot (⭐752)](https://github.com/asavinov/intelligent-trading-bot) - Automatically generating signals and trading based on machine learning and feature engineering
*   [fastquant (⭐1.4k)](https://github.com/enzoampil/fastquant) - fastquant allows you to easily backtest investment strategies with as few as 3 lines of python code.
*   [nautilus\_trader (⭐1.6k)](https://github.com/nautechsystems/nautilus_trader) - A high-performance algorithmic trading platform and event-driven backtester.

### Risk Analysis

*   [pyfolio (⭐5.4k)](https://github.com/quantopian/pyfolio) - Portfolio and risk analytics in Python.
*   [empyrical (⭐1.2k)](https://github.com/quantopian/empyrical) - Common financial risk and performance metrics.
*   [fecon235 (⭐1.1k)](https://github.com/rsvp/fecon235) - Computational tools for financial economics include: Gaussian Mixture model of leptokurtotic risk, adaptive Boltzmann portfolios.
*   [finance](https://pypi.org/project/finance/) - Financial Risk Calculations. Optimized for ease of use through class construction and operator overload.
*   [qfrm](https://pypi.org/project/qfrm/) - Quantitative Financial Risk Management: awesome OOP tools for measuring, managing and visualizing risk of financial instruments and portfolios.
*   [visualize-wealth (⭐136)](https://github.com/benjaminmgross/visualize-wealth) - Portfolio construction and quantitative analysis.
*   [VisualPortfolio (⭐99)](https://github.com/wegamekinglc/VisualPortfolio) - This tool is used to visualize the performance of a portfolio.
*   [universal-portfolios (⭐727)](https://github.com/Marigold/universal-portfolios) - Collection of algorithms for online portfolio selection.
*   [FinQuant (⭐1.3k)](https://github.com/fmilthaler/FinQuant) - A program for financial portfolio management, analysis and optimization.
*   [Empyrial (⭐873)](https://github.com/ssantoshp/Empyrial) - Portfolio's risk and performance analytics and returns predictions.
*   [risktools (⭐25)](https://github.com/bbcho/risktools-dev) - Risk tools for use within the crude and crude products trading space with partial implementation of R's PerformanceAnalytics.
*   [Riskfolio-Lib (⭐2.7k)](https://github.com/dcajasn/Riskfolio-Lib) - Portfolio Optimization and Quantitative Strategic Asset Allocation in Python.
*   [empyrical-reloaded (⭐40)](https://github.com/stefan-jansen/empyrical-reloaded) - Common financial risk and performance metrics. [empyrical (⭐1.2k)](https://github.com/quantopian/empyrical) fork.
*   [pyfolio-reloaded (⭐291)](https://github.com/stefan-jansen/pyfolio-reloaded) - Portfolio and risk analytics in Python. [pyfolio (⭐5.4k)](https://github.com/quantopian/pyfolio) fork.
*   [fortitudo.tech (⭐149)](https://github.com/fortitudo-tech/fortitudo.tech) - Conditional Value-at-Risk (CVaR) portfolio optimization and Entropy Pooling views / stress-testing in Python.

### Factor Analysis

*   [alphalens (⭐3.1k)](https://github.com/quantopian/alphalens) - Performance analysis of predictive alpha factors.
*   [Spectre (⭐544)](https://github.com/Heerozh/spectre) - GPU-accelerated Factors analysis library and Backtester

### Quant Research Environment

*   [Jupyter Quant (⭐51)](https://github.com/gnzsnz/jupyter-quant) - A dockerized Jupyter quant research environment with preloaded tools for quant analysis, statsmodels, pymc, arch, py\_vollib, zipline-reloaded, PyPortfolioOpt, etc.

### Time Series

*   [ARCH (⭐1.3k)](https://github.com/bashtage/arch) - ARCH models in Python.
*   [statsmodels](http://statsmodels.sourceforge.net) - Python module that allows users to explore data, estimate statistical models, and perform statistical tests.
*   [dynts (⭐86)](https://github.com/quantmind/dynts) - Python package for timeseries analysis and manipulation.
*   [PyFlux (⭐2.1k)](https://github.com/RJT1990/pyflux) - Python library for timeseries modelling and inference (frequentist and Bayesian) on models.
*   [tsfresh (⭐8.1k)](https://github.com/blue-yonder/tsfresh) - Automatic extraction of relevant features from time series.
*   [hasura/quandl-metabase](https://platform.hasura.io/hub/projects/anirudhm/quandl-metabase-time-series) - Hasura quickstart to visualize Quandl's timeseries datasets with Metabase.
*   [Facebook Prophet (⭐18k)](https://github.com/facebook/prophet) - Tool for producing high quality forecasts for time series data that has multiple seasonality with linear or non-linear growth.
*   [tsmoothie (⭐706)](https://github.com/cerlymarco/tsmoothie) - A python library for time-series smoothing and outlier detection in a vectorized way.
*   [pmdarima (⭐1.5k)](https://github.com/alkaline-ml/pmdarima) - A statistical library designed to fill the void in Python's time series analysis capabilities, including the equivalent of R's auto.arima function.
*   [gluon-ts (⭐4.3k)](https://github.com/awslabs/gluon-ts) - vProbabilistic time series modeling in Python.

### Calendars

*   [exchange\_calendars (⭐382)](https://github.com/gerrymanoim/exchange_calendars) - Stock Exchange Trading Calendars.
*   [bizdays (⭐74)](https://github.com/wilsonfreitas/python-bizdays) - Business days calculations and utilities.
*   [pandas\_market\_calendars (⭐730)](https://github.com/rsheftel/pandas_market_calendars) - Exchange calendars to use with pandas for trading applications.

### Data Sources

*   [yfinance (⭐12k)](https://github.com/ranaroussi/yfinance) - Yahoo! Finance market data downloader (+faster Pandas Datareader)
*   [findatapy (⭐1.6k)](https://github.com/cuemacro/findatapy) - Python library to download market data via Bloomberg, Quandl, Yahoo etc.
*   [googlefinance (⭐681)](https://github.com/hongtaocai/googlefinance) - Python module to get real-time stock data from Google Finance API.
*   [yahoo-finance (⭐1.3k)](https://github.com/lukaszbanasiak/yahoo-finance) - Python module to get stock data from Yahoo! Finance.
*   [pandas-datareader (⭐2.8k)](https://github.com/pydata/pandas-datareader) - Python module to get data from various sources (Google Finance, Yahoo Finance, FRED, OECD, Fama/French, World Bank, Eurostat...) into Pandas datastructures such as DataFrame, Panel with a caching mechanism.
*   [pandas-finance (⭐150)](https://github.com/davidastephens/pandas-finance) - High level API for access to and analysis of financial data.
*   [pyhoofinance (⭐9)](https://github.com/innes213/pyhoofinance) - Rapidly queries Yahoo Finance for multiple tickers and returns typed data for analysis.
*   [yfinanceapi (⭐9)](https://github.com/Karthik005/yfinanceapi) - Finance API for Python.
*   [yql-finance (⭐16)](https://github.com/slawek87/yql-finance) - yql-finance is simple and fast. API returns stock closing prices for current period of time and current stock ticker (i.e. APPL, GOOGL).
*   [ystockquote (⭐528)](https://github.com/cgoldberg/ystockquote) - Retrieve stock quote data from Yahoo Finance.
*   [wallstreet (⭐1.2k)](https://github.com/mcdallas/wallstreet) - Real time stock and option data.
*   [stock\_extractor (⭐28)](https://github.com/ZachLiuGIS/stock_extractor) - General Purpose Stock Extractors from Online Resources.
*   [Stockex (⭐33)](https://github.com/cttn/Stockex) - Python wrapper for Yahoo! Finance API.
*   [finsymbols (⭐102)](https://github.com/skillachie/finsymbols) - Obtains stock symbols and relating information for SP500, AMEX, NYSE, and NASDAQ.
*   [FRB (⭐160)](https://github.com/avelkoski/FRB) - Python Client for FRED® API.
*   [inquisitor (⭐34)](https://github.com/econdb/inquisitor) - Python Interface to Econdb.com API.
*   [yfi (⭐2)](https://github.com/nickelkr/yfi) - Yahoo! YQL library.
*   [chinesestockapi](https://pypi.org/project/chinesestockapi/) - Python API to get Chinese stock price.
*   [exchange (⭐16)](https://github.com/akarat/exchange) - Get current exchange rate.
*   [ticks (⭐16)](https://github.com/jamescnowell/ticks) - Simple command line tool to get stock ticker data.
*   [pybbg (⭐53)](https://github.com/bpsmith/pybbg) - Python interface to Bloomberg COM APIs.
*   [ccy (⭐76)](https://github.com/lsbardel/ccy) - Python module for currencies.
*   [tushare](https://pypi.org/project/tushare/) - A utility for crawling historical and Real-time Quotes data of China stocks.
*   [jsm](https://pypi.org/project/jsm/) - Get the japanese stock market data.
*   [cn\_stock\_src (⭐34)](https://github.com/jealous/cn_stock_src) - Utility for retrieving basic China stock data from different sources.
*   [coinmarketcap (⭐432)](https://github.com/barnumbirr/coinmarketcap) - Python API for coinmarketcap.
*   [after-hours (⭐35)](https://github.com/datawrestler/after-hours) - Obtain pre market and after hours stock prices for a given symbol.
*   [bronto-python](https://pypi.org/project/bronto-python/) - Bronto API Integration for Python.
*   [pytdx (⭐1.3k)](https://github.com/rainx/pytdx) - Python Interface for retrieving chinese stock realtime quote data from TongDaXin Nodes.
*   [pdblp (⭐238)](https://github.com/matthewgilbert/pdblp) - A simple interface to integrate pandas and the Bloomberg Open API.
*   [tiingo (⭐240)](https://github.com/hydrosquall/tiingo-python) - Python interface for daily composite prices/OHLC/Volume + Real-time News Feeds, powered by the Tiingo Data Platform.
*   [iexfinance (⭐648)](https://github.com/addisonlynch/iexfinance) - Python Interface for retrieving real-time and historical prices and equities data from The Investor's Exchange.
*   [pyEX (⭐403)](https://github.com/timkpaine/pyEX) - Python interface to IEX with emphasis on pandas, support for streaming data, premium data, points data (economic, rates, commodities), and technical indicators.
*   [alpaca-trade-api (⭐1.7k)](https://github.com/alpacahq/alpaca-trade-api-python) - Python interface for retrieving real-time and historical prices from Alpaca API as well as trade execution.
*   [metatrader5](https://pypi.org/project/MetaTrader5/) - API Connector to MetaTrader 5 Terminal
*   [akshare (⭐8.5k)](https://github.com/jindaxiang/akshare) - AkShare is an elegant and simple financial data interface library for Python, built for human beings! <https://akshare.readthedocs.io>
*   [yahooquery (⭐743)](https://github.com/dpguthrie/yahooquery) - Python interface for retrieving data through unofficial Yahoo Finance API.
*   [investpy (⭐1.6k)](https://github.com/alvarobartt/investpy) - Financial Data Extraction from Investing.com with Python! <https://investpy.readthedocs.io/>
*   [yliveticker (⭐134)](https://github.com/yahoofinancelive/yliveticker) - Live stream of market data from Yahoo Finance websocket.
*   [bbgbridge (⭐1)](https://github.com/ran404/bbgbridge) - Easy to use Bloomberg Desktop API wrapper for Python.
*   [alpha\_vantage (⭐4.2k)](https://github.com/RomelTorres/alpha_vantage) - A python wrapper for Alpha Vantage API for financial data.
*   [FinanceDataReader (⭐1.1k)](https://github.com/FinanceData/FinanceDataReader) - Open Source Financial data reader for U.S, Korean, Japanese, Chinese, Vietnamese Stocks
*   [pystlouisfed (⭐12)](https://github.com/TomasKoutek/pystlouisfed) - Python client for Federal Reserve Bank of St. Louis API - FRED, ALFRED, GeoFRED and FRASER.
*   [python-bcb (⭐66)](https://github.com/wilsonfreitas/python-bcb) - Python interface to Brazilian Central Bank web services.
*   [market-prices (⭐73)](https://github.com/maread99/market_prices) - Create meaningful OHLCV datasets from knowledge of [exchange-calendars (⭐382)](https://github.com/gerrymanoim/exchange_calendars) (works out-the-box with data from Yahoo Finance).
*   [tardis-python (⭐107)](https://github.com/tardis-dev/tardis-python) - Python interface for Tardis.dev high frequency crypto market data
*   [lake-api (⭐20)](https://github.com/crypto-lake/lake-api) - Python interface for Crypto Lake high frequency crypto market data
*   [tessa (⭐36)](https://github.com/ymyke/tessa) - simple, hassle-free access to price information of financial assets (currently based on yfinance and pycoingecko), including search and a symbol class.
*   [pandaSDMX (⭐124)](https://github.com/dr-leo/pandaSDMX) - Python package that implements SDMX 2.1 (ISO 17369:2013), a format for exchange of statistical data and metadata used by national statistical agencies, central banks, and international organisations.
*   [cif (⭐50)](https://github.com/LenkaV/CIF) - Python package that include few composite indicators, which summarize multidimensional relationships between individual economic indicators.
*   [finagg (⭐385)](https://github.com/theOGognf/finagg) - finagg is a Python package that provides implementations of popular and free financial APIs, tools for aggregating historical data from those APIs into SQL databases, and tools for transforming aggregated data into features useful for analysis and AI/ML.
*   [FinanceDatabase (⭐2.9k)](https://github.com/JerBouma/FinanceDatabase) - This is a database of 300.000+ symbols containing Equities, ETFs, Funds, Indices, Currencies, Cryptocurrencies and Money Markets.

### Excel Integration

*   [xlwings](https://www.xlwings.org/) - Make Excel fly with Python.
*   [openpyxl](https://openpyxl.readthedocs.io/en/latest/) - Read/Write Excel 2007 xlsx/xlsm files.
*   [xlrd (⭐2.1k)](https://github.com/python-excel/xlrd) - Library for developers to extract data from Microsoft Excel spreadsheet files.
*   [xlsxwriter](https://xlsxwriter.readthedocs.io/) - Write files in the Excel 2007+ XLSX file format.
*   [xlwt (⭐1k)](https://github.com/python-excel/xlwt) - Library to create spreadsheet files compatible with MS Excel 97/2000/XP/2003 XLS files, on any platform.
*   [DataNitro](https://datanitro.com/) - DataNitro also offers full-featured Python-Excel integration, including UDFs. Trial downloads are available, but users must purchase a license.
*   [xlloop](http://xlloop.sourceforge.net) - XLLoop is an open source framework for implementing Excel user-defined functions (UDFs) on a centralised server (a function server).
*   [expy](http://www.bnikolic.co.uk/expy/expy.html) - The ExPy add-in allows easy use of Python directly from within an Microsoft Excel spreadsheet, both to execute arbitrary code and to define new Excel functions.
*   [pyxll](https://www.pyxll.com) - PyXLL is an Excel add-in that enables you to extend Excel using nothing but Python code.

### Visualization

*   [D-Tale (⭐4.6k)](https://github.com/man-group/dtale) - Visualizer for pandas dataframes and xarray datasets.
*   [mplfinance (⭐3.4k)](https://github.com/matplotlib/mplfinance) - matplotlib utilities for the visualization, and visual analysis, of financial data.
*   [finplot (⭐854)](https://github.com/highfestiva/finplot) - Performant and effortless finance plotting for Python.
*   [finvizfinance (⭐415)](https://github.com/lit26/finvizfinance) - Finviz analysis python library.
*   [market-analy (⭐29)](https://github.com/maread99/market_analy) - Analysis and interactive charting using [market-prices (⭐73)](https://github.com/maread99/market_prices) and bqplot.

## R

### Numerical Libraries & Data Structures

*   [xts (⭐217)](https://github.com/joshuaulrich/xts) - eXtensible Time Series: Provide for uniform handling of R's different time-based data classes by extending zoo, maximizing native format information preservation and allowing for user level customization and extension, while simplifying cross-class interoperability.
*   [data.table (⭐3.5k)](https://github.com/Rdatatable/data.table) - Extension of data.frame: Fast aggregation of large data (e.g. 100GB in RAM), fast ordered joins, fast add/modify/delete of columns by group using no copies at all, list columns and a fast file reader (fread). Offers a natural and flexible syntax, for faster development.
*   [sparseEigen (⭐11)](https://github.com/dppalomar/sparseEigen) - Sparse principal component analysis.
*   [TSdbi](http://tsdbi.r-forge.r-project.org/) - Provides a common interface to time series databases.
*   [tseries](https://cran.r-project.org/web/packages/tseries/index.html) - Time Series Analysis and Computational Finance.
*   [zoo](https://cran.r-project.org/web/packages/zoo/index.html) - S3 Infrastructure for Regular and Irregular Time Series (Z's Ordered Observations).
*   [tis](https://cran.r-project.org/web/packages/tis/index.html) - Functions and S3 classes for time indexes and time indexed series, which are compatible with FAME frequencies.
*   [tfplot](https://cran.r-project.org/web/packages/tfplot/index.html) - Utilities for simple manipulation and quick plotting of time series data.
*   [tframe](https://cran.r-project.org/web/packages/tframe/index.html) - A kernel of functions for programming time series methods in a way that is relatively independently of the representation of time.

### Data Sources

*   [IBrokers](https://cran.r-project.org/web/packages/IBrokers/index.html) - Provides native R access to Interactive Brokers Trader Workstation API.
*   [Rblpapi (⭐165)](https://github.com/Rblp/Rblpapi) - An R Interface to 'Bloomberg' is provided via the 'Blp API'.
*   [Quandl](https://www.quandl.com/tools/r) - Get Financial Data Directly Into R.
*   [Rbitcoin (⭐57)](https://github.com/jangorecki/Rbitcoin) - Unified markets API interface (bitstamp, kraken, btce, bitmarket).
*   [GetTDData (⭐20)](https://github.com/msperlin/GetTDData) - Downloads and aggregates data for Brazilian government issued bonds directly from the website of Tesouro Direto.
*   [GetHFData (⭐38)](https://github.com/msperlin/GetHFData) - Downloads and aggregates high frequency trading data for Brazilian instruments directly from Bovespa ftp site.
*   [Reddit WallstreetBets API](https://dashboard.nbshare.io/apps/reddit/api/) - Provides daily top 50 stocks from reddit (subreddit) Wallstreetbets and their sentiments via the API.
*   [td (⭐12)](https://github.com/eddelbuettel/td) - Interfaces the 'twelvedata' API for stocks and (digital and standard) currencies.
*   [rbcb (⭐89)](https://github.com/wilsonfreitas/rbcb) - R interface to Brazilian Central Bank web services.
*   [rb3 (⭐69)](https://github.com/ropensci/rb3) - A bunch of downloaders and parsers for data delivered from B3.
*   [simfinapi (⭐17)](https://github.com/matthiasgomolka/simfinapi) - Makes 'SimFin' data (<https://simfin.com/>) easily accessible in R.

### Financial Instruments and Pricing

*   [RQuantLib (⭐117)](https://github.com/eddelbuettel/rquantlib) - RQuantLib connects GNU R with QuantLib.
*   [quantmod](https://cran.r-project.org/web/packages/quantmod/index.html) - Quantitative Financial Modelling Framework.
*   [Rmetrics](https://www.rmetrics.org) - The premier open source software solution for teaching and training quantitative finance.
    *   [fAsianOptions](https://cran.r-project.org/web/packages/fAsianOptions/index.html) - EBM and Asian Option Valuation.
    *   [fAssets](https://cran.r-project.org/web/packages/fAssets/index.html) - Analysing and Modelling Financial Assets.
    *   [fBasics](https://cran.r-project.org/web/packages/fBasics/index.html) - Markets and Basic Statistics.
    *   [fBonds](https://cran.r-project.org/web/packages/fBonds/index.html) - Bonds and Interest Rate Models.
    *   [fExoticOptions](https://cran.r-project.org/web/packages/fExoticOptions/index.html) - Exotic Option Valuation.
    *   [fOptions](https://cran.r-project.org/web/packages/fOptions/index.html) - Pricing and Evaluating Basic Options.
    *   [fPortfolio](https://cran.r-project.org/web/packages/fPortfolio/index.html) - Portfolio Selection and Optimization.
*   [portfolio (⭐15)](https://github.com/dgerlanc/portfolio) - Analysing equity portfolios.
*   [sparseIndexTracking (⭐48)](https://github.com/dppalomar/sparseIndexTracking) - Portfolio design to track an index.
*   [covFactorModel (⭐29)](https://github.com/dppalomar/covFactorModel) - Covariance matrix estimation via factor models.
*   [riskParityPortfolio (⭐100)](https://github.com/dppalomar/riskParityPortfolio) - Blazingly fast design of risk parity portfolios.
*   [sde](https://cran.r-project.org/web/packages/sde/index.html) - Simulation and Inference for Stochastic Differential Equations.
*   [YieldCurve](https://cran.r-project.org/web/packages/YieldCurve/index.html) - Modelling and estimation of the yield curve.
*   [SmithWilsonYieldCurve](https://cran.r-project.org/web/packages/SmithWilsonYieldCurve/index.html) - Constructs a yield curve by the Smith-Wilson method from a table of LIBOR and SWAP rates.
*   [ycinterextra](https://cran.r-project.org/web/packages/ycinterextra/index.html) - Yield curve or zero-coupon prices interpolation and extrapolation.
*   [AmericanCallOpt](https://cran.r-project.org/web/packages/AmericanCallOpt/index.html) - This package includes pricing function for selected American call options with underlying assets that generate payouts.
*   [VarSwapPrice](https://cran.r-project.org/web/packages/VarSwapPrice/index.html) - Pricing a variance swap on an equity index.
*   [RND](https://cran.r-project.org/web/packages/RND/index.html) - Risk Neutral Density Extraction Package.
*   [LSMonteCarlo](https://cran.r-project.org/web/packages/LSMonteCarlo/index.html) - American options pricing with Least Squares Monte Carlo method.
*   [OptHedging](https://cran.r-project.org/web/packages/OptHedging/index.html) - Estimation of value and hedging strategy of call and put options.
*   [tvm](https://cran.r-project.org/web/packages/tvm/index.html) - Time Value of Money Functions.
*   [OptionPricing](https://cran.r-project.org/web/packages/OptionPricing/index.html) - Option Pricing with Efficient Simulation Algorithms.
*   [credule (⭐5)](https://github.com/blenezet/credule) - Credit Default Swap Functions.
*   [derivmkts](https://cran.r-project.org/web/packages/derivmkts/index.html) - Functions and R Code to Accompany Derivatives Markets.
*   [FinCal (⭐21)](https://github.com/felixfan/FinCal) - Package for time value of money calculation, time series analysis and computational finance.
*   [r-quant (⭐30)](https://github.com/artyyouth/r-quant) - R code for quantitative analysis in finance.
*   [options.studies (⭐6)](https://github.com/taylorizing/options.studies) - options trading studies functions for use with options.data package and shiny.
*   [PortfolioAnalytics (⭐73)](https://github.com/braverock/PortfolioAnalytics) - Portfolio Analysis, Including Numerical Methods for Optimizationof Portfolios.
*   [fmbasics (⭐12)](https://github.com/imanuelcostigan/fmbasics) - Financial Market Building Blocks.
*   [R-fixedincome (⭐48)](https://github.com/wilsonfreitas/R-fixedincome) - Fixed income tools for R.

### Trading

*   [backtest](https://cran.r-project.org/web/packages/backtest/index.html) - Exploring Portfolio-Based Conjectures About Financial Instruments.
*   [pa](https://cran.r-project.org/web/packages/pa/index.html) - Performance Attribution for Equity Portfolios.
*   [TTR (⭐320)](https://github.com/joshuaulrich/TTR) - Technical Trading Rules.
*   [QuantTools](https://quanttools.bitbucket.io/_site/index.html) - Enhanced Quantitative Trading Modelling.
*   [blotter (⭐110)](https://github.com/braverock/blotter) - Transaction infrastructure for defining instruments, transactions, portfolios and accounts for trading systems and simulation. Provides portfolio support for multi-asset class and multi-currency portfolios. Actively maintained and developed.

### Backtesting

*   [quantstrat (⭐277)](https://github.com/braverock/quantstrat) - Transaction-oriented infrastructure for constructing trading systems and simulation. Provides support for multi-asset class and multi-currency portfolios for backtesting and other financial research.

### Risk Analysis

*   [PerformanceAnalytics (⭐203)](https://github.com/braverock/PerformanceAnalytics) - Econometric tools for performance and risk analysis.

### Factor Analysis

*   [FactorAnalytics (⭐63)](https://github.com/braverock/FactorAnalytics) - The FactorAnalytics package contains fitting and analysis methods for the three main types of factor models used in conjunction with portfolio construction, optimization and risk management, namely fundamental factor models, time series factor models and statistical factor models.
*   [Expected Returns (⭐35)](https://github.com/JustinMShea/ExpectedReturns) - Solutions for enhancing portfolio diversification and replications of seminal papers with R, most of which are discussed in one of the best investment references of the recent decade, Expected Returns: An Investors Guide to Harvesting Market Rewards by Antti Ilmanen.

### Time Series

*   [tseries](https://cran.r-project.org/web/packages/tseries/index.html) - Time Series Analysis and Computational Finance.
*   [fGarch](https://cran.r-project.org/web/packages/fGarch/index.html) - Rmetrics - Autoregressive Conditional Heteroskedastic Modelling.
*   [timeSeries](https://cran.r-project.org/web/packages/timeSeries/index.html) - Rmetrics - Financial Time Series Objects.
*   [rugarch (⭐19)](https://github.com/alexiosg/rugarch) - Univariate GARCH Models.
*   [rmgarch (⭐11)](https://github.com/alexiosg/rmgarch) - Multivariate GARCH Models.
*   [tidypredict (⭐2)](https://github.com/edgararuiz/tidypredict) - Run predictions inside the database <https://tidypredict.netlify.com/>.
*   [tidyquant (⭐833)](https://github.com/business-science/tidyquant) - Bringing financial analysis to the tidyverse.
*   [timetk (⭐597)](https://github.com/business-science/timetk) - A toolkit for working with time series in R.
*   [tibbletime (⭐179)](https://github.com/business-science/tibbletime) - Built on top of the tidyverse, tibbletime is an extension that allows for the creation of time aware tibbles through the setting of a time index.
*   [matrixprofile (⭐356)](https://github.com/matrix-profile-foundation/matrixprofile) - Time series data mining library built on top of the novel Matrix Profile data structure and algorithms.
*   [garchmodels (⭐34)](https://github.com/AlbertoAlmuinha/garchmodels) - A parsnip backend for GARCH models.

### Calendars

*   [timeDate](https://cran.r-project.org/web/packages/timeDate/index.html) - Chronological and Calendar Objects
*   [bizdays (⭐53)](https://github.com/wilsonfreitas/R-bizdays) - Business days calculations and utilities

## Matlab

### FrameWorks

*   [QUANTAXIS (⭐7.9k)](https://github.com/yutiansut/quantaxis) - Integrated Quantitative Toolbox with Matlab.

## Julia

*   [Lucky.jl (⭐5)](https://github.com/oliviermilla/Lucky.jl) - Modular, asynchronous trading engine in pure Julia.
*   [QuantLib.jl (⭐135)](https://github.com/pazzo83/QuantLib.jl) - Quantlib implementation in pure Julia.
*   [Ito.jl (⭐36)](https://github.com/aviks/Ito.jl) - A Julia package for quantitative finance.
*   [TALib.jl (⭐50)](https://github.com/femtotrader/TALib.jl) - A Julia wrapper for TA-Lib.
*   [IncTA.jl (⭐15)](https://github.com/femtotrader/IncTA.jl) - Julia Incremental Technical Analysis Indicators
*   [Miletus.jl (⭐81)](https://github.com/JuliaComputing/Miletus.jl) - A financial contract definition, modeling language, and valuation framework.
*   [Temporal.jl (⭐99)](https://github.com/dysonance/Temporal.jl) - Flexible and efficient time series class & methods.
*   [Indicators.jl (⭐212)](https://github.com/dysonance/Indicators.jl) - Financial market technical analysis & indicators on top of Temporal.
*   [Strategems.jl (⭐163)](https://github.com/dysonance/Strategems.jl) - Quantitative systematic trading strategy development and backtesting.
*   [TimeSeries.jl (⭐343)](https://github.com/JuliaStats/TimeSeries.jl) - Time series toolkit for Julia.
*   [MarketTechnicals.jl (⭐125)](https://github.com/JuliaQuant/MarketTechnicals.jl) - Technical analysis of financial time series on top of TimeSeries.
*   [MarketData.jl (⭐138)](https://github.com/JuliaQuant/MarketData.jl) - Time series market data.
*   [TimeFrames.jl (⭐4)](https://github.com/femtotrader/TimeFrames.jl) - A Julia library that defines TimeFrame (essentially for resampling TimeSeries).
*   [DataFrames.jl (⭐1.7k)](https://github.com/JuliaData/DataFrames.jl) - In-memory tabular data in Julia
*   [TSFrames.jl (⭐87)](https://github.com/xKDR/TSFrames.jl) - Handle timeseries data on top of the powerful and mature DataFrames.jl

## Java

*   [Strata](http://strata.opengamma.io/) - Modern open-source analytics and market risk library designed and written in Java.
*   [JQuantLib (⭐120)](https://github.com/frgomes/jquantlib) - JQuantLib is a free, open-source, comprehensive framework for quantitative finance, written in 100% Java.
*   [finmath.net](http://finmath.net) - Java library with algorithms and methodologies related to mathematical finance.
*   [quantcomponents (⭐163)](https://github.com/lsgro/quantcomponents) - Free Java components for Quantitative Finance and Algorithmic Trading.
*   [DRIP](https://lakshmidrip.github.io/DRIP) - Fixed Income, Asset Allocation, Transaction Cost Analysis, XVA Metrics Libraries.
*   [ta4j (⭐2k)](https://github.com/ta4j/ta4j) - A Java library for technical analysis.

## JavaScript

*   [finance.js (⭐1.2k)](https://github.com/ebradyjobory/finance.js) - A JavaScript library for common financial calculations.
*   [portfolio-allocation (⭐171)](https://github.com/lequant40/portfolio_allocation_js) - PortfolioAllocation is a JavaScript library designed to help constructing financial portfolios made of several assets: bonds, commodities, cryptocurrencies, currencies, exchange traded funds (ETFs), mutual funds, stocks...
*   [Ghostfolio (⭐3.6k)](https://github.com/ghostfolio/ghostfolio) - Wealth management software to keep track of financial assets like stocks, ETFs or cryptocurrencies and make solid, data-driven investment decisions.
*   [IndicatorTS (⭐247)](https://github.com/cinar/indicatorts) - Indicator is a TypeScript module providing various stock technical analysis indicators, strategies, and a backtest framework for trading.
*   [ccxt (⭐32k)](https://github.com/ccxt/ccxt) - A JavaScript / Python / PHP cryptocurrency trading API with support for more than 100 bitcoin/altcoin exchanges.
*   [PENDAX (⭐41)](https://github.com/CompendiumFi/PENDAX-SDK) - Javascript SDK for Trading/Data API and Websockets for FTX, FTXUS, OKX, Bybit, & More.

### Data Visualization

*   [QUANTAXIS\_Webkit (⭐38)](https://github.com/yutiansut/QUANTAXIS_Webkit) - An awesome visualization center based on quantaxis.

## Haskell

*   [quantfin (⭐133)](https://github.com/boundedvariation/quantfin) - quant finance in pure haskell.
*   [Haxcel (⭐31)](https://github.com/MarcusRainbow/Haxcel) - Excel Addin for Haskell.
*   [Ffinar (⭐2)](https://github.com/MarcusRainbow/Ffinar) - A financial maths library in Haskell.

## Scala

*   [QuantScale (⭐46)](https://github.com/choucrifahed/quantscale) - Scala Quantitative Finance Library.
*   [Scala Quant (⭐10)](https://github.com/frankcash/Scala-Quant) - Scala library for working with stock data from IFTTT recipes or Google Finance.

## Ruby

*   [Jiji (⭐239)](https://github.com/unageanu/jiji2) - Open Source Forex algorithmic trading framework using OANDA REST API.

## Elixir/Erlang

*   [Tai (⭐449)](https://github.com/fremantle-capital/tai) - Open Source composable, real time, market data and trade execution toolkit.
*   [Workbench (⭐111)](https://github.com/fremantle-industries/workbench) - From Idea to Execution - Manage your trading operation across a globally distributed cluster
*   [Prop (⭐44)](https://github.com/fremantle-industries/prop) - An open and opinionated trading platform using productive & familiar open source libraries and tools for strategy research, execution and operation.

## Golang

*   [Kelp (⭐1.1k)](https://github.com/stellar/kelp) - Kelp is an open-source Golang algorithmic cryptocurrency trading bot that runs on centralized exchanges and Stellar DEX (command-line usage and desktop GUI).
*   [marketstore (⭐1.8k)](https://github.com/alpacahq/marketstore) - DataFrame Server for Financial Timeseries Data.
*   [IndicatorGo (⭐413)](https://github.com/cinar/indicator) - IndicatorGo is a Golang module providing various stock technical analysis indicators, strategies, and a backtest framework for trading.

## CPP

*   [QuantLib (⭐4.9k)](https://github.com/lballabio/QuantLib) - The QuantLib project is aimed at providing a comprehensive software framework for quantitative finance.
*   [TradeFrame (⭐434)](https://github.com/rburkholder/trade-frame) - C++ 17 based framework/library (with sample applications) for testing options based automated trading ideas using DTN IQ real time data feed and Interactive Brokers (TWS API) for trade execution. Comes with built-in [Option Greeks/IV (⭐434)](https://github.com/rburkholder/trade-frame/tree/master/lib/TFOptions) calculation library.

## Frameworks

*   [QuantLib (⭐4.9k)](https://github.com/lballabio/QuantLib) - The QuantLib project is aimed at providing a comprehensive software framework for quantitative finance.
    *   [JQuantLib (⭐120)](https://github.com/frgomes/jquantlib) - Java port.
    *   [RQuantLib (⭐117)](https://github.com/eddelbuettel/rquantlib) - R port.
    *   [QuantLibAddin](https://www.quantlib.org/quantlibaddin/) - Excel support.
    *   [QuantLibXL](https://www.quantlib.org/quantlibxl/) - Excel support.
    *   [QLNet (⭐375)](https://github.com/amaggiulli/qlnet) - .Net port.
    *   [PyQL (⭐923)](https://github.com/enthought/pyql) - Python port.
    *   [QuantLib.jl (⭐135)](https://github.com/pazzo83/QuantLib.jl) - Julia port.
    *   [QuantLib-Python Documentation](https://quantlib-python-docs.readthedocs.io/) - Documentation for the Python bindings for the QuantLib library
    *   [QuantLib with Automatic Differention enabled (⭐12)](https://github.com/auto-differentiation/quantlib-xad) - Integration of Automatic Differentiation with the QuantLib library
*   [TA-Lib](https://ta-lib.org) - perform technical analysis of financial market data.
    *   [ta-lib-python (⭐9.1k)](https://github.com/TA-Lib/ta-lib-python)
    *   [ta-lib (⭐358)](https://github.com/TA-Lib/ta-lib)
*   [Portfolio Optimizer](https://portfoliooptimizer.io/) - Portfolio Optimizer is a Web API for portfolio analysis and optimization.

## CSharp

*   [QuantConnect (⭐8.8k)](https://github.com/QuantConnect/Lean) - Lean Engine is an open-source fully managed C# algorithmic trading engine built for desktop and cloud usage.
*   [StockSharp (⭐6.7k)](https://github.com/StockSharp/StockSharp) - Algorithmic trading and quantitative trading open source platform to develop trading robots (stock markets, forex, crypto, bitcoins, and options).
*   [TDAmeritrade.DotNetCore (⭐54)](https://github.com/NVentimiglia/TDAmeritrade.DotNetCore) - Free, open-source .NET Client for the TD Ameritrade Trading Platform. Helps developers integrate TD Ameritrade API into custom trading solutions.

## Rust

*   [QuantMath (⭐347)](https://github.com/MarcusRainbow/QuantMath) - Financial maths library for risk-neutral pricing and risk
*   [Barter (⭐617)](https://github.com/barter-rs/barter-rs) - Open-source Rust framework for building event-driven live-trading & backtesting systems
*   [LFEST (⭐43)](https://github.com/MathisWellmann/lfest-rs) - Simulated perpetual futures exchange to trade your strategy against.
*   [TradeAggregation (⭐55)](https://github.com/MathisWellmann/trade_aggregation-rs) - Aggregate trades into user-defined candles using information driven rules.
*   [SlidingFeatures (⭐36)](https://github.com/MathisWellmann/sliding_features-rs) - Chainable tree-like sliding windows for signal processing and technical analysis.
*   [RustQuant (⭐876)](https://github.com/avhz/RustQuant) - Quantitative finance library written in Rust.
*   [finalytics (⭐8)](https://github.com/Nnamdi-sys/finalytics) - A rust library for financial data analysis.

## Reproducing Works, Training & Books

*   [Derman Papers (⭐357)](https://github.com/MarcosCarreira/DermanPapers) - Notebooks that replicate original quantitative finance papers from Emanuel Derman.
*   [ML-Quant](https://www.ml-quant.com/) - Top Quant resources like ArXiv (sanity), SSRN, RePec, Journals, Podcasts, Videos, and Blogs.
*   [volatility-trading (⭐1.5k)](https://github.com/jasonstrimpel/volatility-trading) - A complete set of volatility estimators based on Euan Sinclair's Volatility Trading.
*   [quant (⭐294)](https://github.com/paulperry/quant) - Quantitative Finance and Algorithmic Trading exhaust; mostly ipython notebooks based on Quantopian, Zipline, or Pandas.
*   [fecon235 (⭐1.1k)](https://github.com/rsvp/fecon235) - Open source project for software tools in financial economics. Many jupyter notebook to verify theoretical ideas and practical methods interactively.
*   [Quantitative-Notebooks (⭐941)](https://github.com/LongOnly/Quantitative-Notebooks) - Educational notebooks on quantitative finance, algorithmic trading, financial modelling and investment strategy
*   [QuantEcon](https://quantecon.org/) - Lecture series on economics, finance, econometrics and data science; QuantEcon.py, QuantEcon.jl, notebooks
*   [FinanceHub (⭐553)](https://github.com/Finance-Hub/FinanceHub) - Resources for Quantitative Finance
*   [Python\_Option\_Pricing (⭐593)](https://github.com/dedwards25/Python_Option_Pricing) - An library to price financial options written in Python. Includes: Black Scholes, Black 76, Implied Volatility, American, European, Asian, Spread Options.
*   [python-training (⭐3.7k)](https://github.com/jpmorganchase/python-training) - J.P. Morgan's Python training for business analysts and traders.
*   [Stock\_Analysis\_For\_Quant (⭐1.6k)](https://github.com/LastAncientOne/Stock_Analysis_For_Quant) - Different Types of Stock Analysis in Excel, Matlab, Power BI, Python, R, and Tableau.
*   [algorithmic-trading-with-python (⭐2.4k)](https://github.com/chrisconlan/algorithmic-trading-with-python) - Source code for Algorithmic Trading with Python (2020) by Chris Conlan.
*   [MEDIUM\_NoteBook (⭐2k)](https://github.com/cerlymarco/MEDIUM_NoteBook) - Repository containing notebooks of [cerlymarco](https://github.com/cerlymarco)'s posts on Medium.
*   [QuantFinance (⭐327)](https://github.com/PythonCharmers/QuantFinance) - Training materials in quantitative finance.
*   [IPythonScripts (⭐140)](https://github.com/mgroncki/IPythonScripts) - Tutorials about Quantitative Finance in Python and QuantLib: Pricing, xVAs, Hedging, Portfolio Optimisation, Machine Learning and Deep Learning.
*   [Computational-Finance-Course (⭐318)](https://github.com/LechGrzelak/Computational-Finance-Course) - Materials for the course of Computational Finance.
*   [Machine-Learning-for-Asset-Managers (⭐438)](https://github.com/emoen/Machine-Learning-for-Asset-Managers) - Implementation of code snippets, exercises and application to live data from Machine Learning for Asset Managers (Elements in Quantitative Finance) written by Prof. Marcos López de Prado.
*   [Python-for-Finance-Cookbook (⭐699)](https://github.com/PacktPublishing/Python-for-Finance-Cookbook) - Python for Finance Cookbook, published by Packt.
*   [modelos\_vol\_derivativos (⭐54)](https://github.com/ysaporito/modelos_vol_derivativos) - "Modelos de Volatilidade para Derivativos" book's Jupyter notebooks
*   [NMOF (⭐35)](https://github.com/enricoschumann/NMOF) - Functions, examples and data from the first and the second edition of "Numerical Methods and Optimization in Finance" by M. Gilli, D. Maringer and E. Schumann (2019, ISBN:978-0128150658).
*   [py4fi2nd (⭐1.3k)](https://github.com/yhilpisch/py4fi2nd) - Jupyter Notebooks and code for Python for Finance (2nd ed., O'Reilly) by Yves Hilpisch.
*   [aiif (⭐275)](https://github.com/yhilpisch/aiif) - Jupyter Notebooks and code for the book Artificial Intelligence in Finance (O'Reilly) by Yves Hilpisch.
*   [py4at (⭐625)](https://github.com/yhilpisch/py4at) - Jupyter Notebooks and code for the book Python for Algorithmic Trading (O'Reilly) by Yves Hilpisch.
*   [dawp (⭐561)](https://github.com/yhilpisch/dawp) - Jupyter Notebooks and code for Derivatives Analytics with Python (Wiley Finance) by Yves Hilpisch.
*   [dx (⭐682)](https://github.com/yhilpisch/dx) - DX Analytics | Financial and Derivatives Analytics with Python.
*   [QuantFinanceBook (⭐373)](https://github.com/LechGrzelak/QuantFinanceBook) - Quantitative Finance book.
*   [rough\_bergomi (⭐103)](https://github.com/ryanmccrickerd/rough_bergomi) - A Python implementation of the rough Bergomi model.
*   [frh-fx (⭐8)](https://github.com/ryanmccrickerd/frh-fx) - A python implementation of the fast-reversion Heston model of Mechkov for FX purposes.
*   [Value Investing Studies (⭐79)](https://github.com/euclidjda/value-investing-studies) - A collection of data analysis studies that examine the performance and characteristics of value investing over long periods of time.
*   [Machine Learning Asset Management (⭐1.6k)](https://github.com/firmai/machine-learning-asset-management) - Machine Learning in Asset Management (by @firmai).
*   [Deep Learning Machine Learning Stock (⭐1.2k)](https://github.com/LastAncientOne/Deep-Learning-Machine-Learning-Stock) - Deep Learning and Machine Learning stocks represent a promising long-term or short-term opportunity for investors and traders.
*   [Technical Analysis and Feature Engineering (⭐103)](https://github.com/jo-cho/Technical_Analysis_and_Feature_Engineering) - Feature Engineering and Feature Importance of Machine Learning in Financial Market.
*   [Differential Machine Learning and Axes that matter by Brian Huge and Antoine Savine (⭐133)](https://github.com/differential-machine-learning/notebooks) - Implement, demonstrate, reproduce and extend the results of the Risk articles 'Differential Machine Learning' (2020) and 'PCA with a Difference' (2021) by Huge and Savine, and cover implementation details left out from the papers.
*   [systematictradingexamples (⭐288)](https://github.com/robcarver17/systematictradingexamples) - Examples of code related to book [Systematic Trading](https://github.com/wilsonfreitas/awesome-quant/blob/master/README.md/www.systematictrading.org) and [blog](http://qoppac.blogspot.com)
*   [pysystemtrade\_examples (⭐169)](https://github.com/robcarver17/pysystemtrade_examples) - Examples using pysystemtrade for Robert Carver's [blog](http://qoppac.blogspot.com).
*   [ML\_Finance\_Codes (⭐1.3k)](https://github.com/mfrdixon/ML_Finance_Codes) - Machine Learning in Finance: From Theory to Practice Book
*   [Hands-On Machine Learning for Algorithmic Trading (⭐1.3k)](https://github.com/packtpublishing/hands-on-machine-learning-for-algorithmic-trading) - Hands-On Machine Learning for Algorithmic Trading, published by Packt
*   [financialnoob-misc (⭐25)](https://github.com/financialnoob/misc) - Codes from @financialnoob's posts
*   [MesoSim Options Trading Strategy Library (⭐6)](https://github.com/deltaray-io/strategy-library) - Free and public Options Trading strategy library for MesoSim.
*   [Quant-Finance-With-Python-Code (⭐54)](https://github.com/lingyixu/Quant-Finance-With-Python-Code) - Repo for code examples in Quantitative Finance with Python by Chris Kelliher
*   [QuantFinanceTraining (⭐11)](https://github.com/JoaoJungblut/QuantFinanceTraining) - This repository contains codes that were executed during my training in the CQF (Certificate in Quantitative Finance). The codes are organized by class, facilitating navigation and reference.
*   [Statistical-Learning-based-Portfolio-Optimization (⭐10)](https://github.com/YannickKae/Statistical-Learning-based-Portfolio-Optimization) - This R Shiny App utilizes the Hierarchical Equal Risk Contribution (HERC) approach, a modern portfolio optimization method developed by Raffinot (2018).
*   [book\_irds3 (⭐42)](https://github.com/attack68/book_irds3) - Code repository for Pricing and Trading Interest Rate Derivatives.
*   [Autoencoder-Asset-Pricing-Models (⭐43)](https://github.com/RichardS0268/Autoencoder-Asset-Pricing-Models) - Reimplementation of Autoencoder Asset Pricing Models ([GKX, 2019](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3335536)).
*   [Finance](https://github.com/shashankvemuri/Finance) - 150+ quantitative finance Python programs to help you gather, manipulate, and analyze stock market data.
*   [101\_formulaic\_alphas (⭐5)](https://github.com/ram-ki/101_formulaic_alphas) - Implementation of [101 formulaic alphas](https://arxiv.org/ftp/arxiv/papers/1601/1601.00991.pdf) using qstrader.

