# Awesome Trading Resources [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of open-source trading tools, libraries, datasets, and educational resources for algorithmic trading, quantitative finance, and risk management.

Contributions welcome! Please read the [contribution guidelines](#contributing) before submitting a PR.

---

## Contents

- [Trading Calculators & Tools](#trading-calculators--tools)
- [Algorithmic Trading Frameworks](#algorithmic-trading-frameworks)
- [Technical Analysis Libraries](#technical-analysis-libraries)
- [Market Data & APIs](#market-data--apis)
- [Backtesting](#backtesting)
- [Risk Management](#risk-management)
- [Order Flow & Market Microstructure](#order-flow--market-microstructure)
- [Machine Learning for Trading](#machine-learning-for-trading)
- [Forex Trading](#forex-trading)
- [Gold & Commodities](#gold--commodities)
- [Crypto Trading](#crypto-trading)
- [Datasets](#datasets)
- [Educational Resources](#educational-resources)
- [Community & Forums](#community--forums)

---

## Trading Calculators & Tools

- [gfil-trading-calculators](https://github.com/liudapao880807-arch/gfil-trading-calculators) - Open-source Python + JavaScript library with 22 trading calculators: position sizing, pip value, ATR, Fibonacci, Kelly criterion, drawdown, risk-reward, margin, compound interest. Covers Forex, Gold (XAUUSD), Crypto, Indices. [PyPI](https://pypi.org/project/gfil-calculators/) | [npm](https://www.npmjs.com/package/gfil-trading-calculators) | [Live Demo](https://blog.quant-view.xyz/tools/position-size-calculator.html)
- [position-sizing-tools](https://github.com/topics/position-sizing) - GitHub topic: repos related to position sizing.
- [forex-calculator](https://github.com/topics/forex-calculator) - GitHub topic: Forex calculator tools.

## Algorithmic Trading Frameworks

- [Freqtrade](https://github.com/freqtrade/freqtrade) - Open-source crypto trading bot with strategy optimization, backtesting, and Dry-Run mode.
- [Hummingbot](https://github.com/hummingbot/hummingbot) - Open-source crypto market-making and arbitrage bot.
- [Jesse](https://github.com/jesse-ai/jesse) - Advanced crypto trading framework with AI-powered strategy research.
- [NautilusTrader](https://github.com/nautechsystems/nautilusTrader) - High-performance algorithmic trading platform and backtesting engine written in Rust/Cython.
- [VectorBT](https://github.com/polakowo/vectorbt) - Python library for backtesting and analyzing trading strategies at scale with vectorized operations.
- [Zipline](https://github.com/quantopian/zipline) - Python algorithmic trading library originally developed by Quantopian.
- [Backtrader](https://github.com/mementum/backtrader) - Python backtesting library for trading strategies.

## Technical Analysis Libraries

- [TA-Lib](https://github.com/ta-lib/ta-lib-python) - Python wrapper for TA-Lib: 150+ technical analysis indicators (RSI, MACD, Bollinger, etc.).
- [pandas-ta](https://github.com/twopirllc/pandas-ta) - Technical analysis indicators as pandas extensions. 130+ indicators.
- [tulipy](https://github.com/cirla/tulipy) - Python wrapper for Tulip Indicators: 104 technical analysis indicators in C.
- [ta4j](https://github.com/ta4j/ta4j) - Java library for technical analysis.

## Market Data & APIs

- [yfinance](https://github.com/ranaroussi/yfinance) - Download market data from Yahoo Finance.
- [ccxt](https://github.com/ccxt/ccxt) - CryptoExchange trading library: unified API for 100+ crypto exchanges.
- [Alpha Vantage](https://www.alphavantage.co/) - Free APIs for real-time and historical stock, forex, and crypto data.
- [Polygon.io](https://polygon.io/) - Market data APIs with WebSocket streaming for stocks, options, forex, and crypto.
- [Twelve Data](https://twelvedata.com/) - Financial data APIs with WebSocket support.
- [OANDA API](https://developer.oanda.com/) - REST API for forex trading and historical data.
- [Dukascopy Data](https://www.dukascopy.com/swiss/english/marketwatch/historical/) - Free tick-level forex data.

## Backtesting

- [Backtrader](https://github.com/mementum/backtrader) - Event-driven backtesting engine.
- [VectorBT](https://github.com/polakowo/vectorbt) - Vectorized backtesting for rapid prototyping.
- [Zipline](https://github.com/quantopian/zipline) - Pipeline-based backtesting from Quantopian.
- [Lean](https://github.com/QuantConnect/Lean) - Algorithmic trading engine by QuantConnect (C#/Python).
- [FinRL](https://github.com/AI4Finance-Foundation/FinRL) - Deep reinforcement learning framework for automated trading.

## Risk Management

- [gfil-trading-calculators](https://github.com/liudapao880807-arch/gfil-trading-calculators) - Position sizing, Kelly criterion, drawdown calculator, risk-reward ratio, margin calculator.
- [empyrical](https://github.com/quantopian/empyrical) - Common financial risk metrics: Sharpe, Sortino, max drawdown, Calmar.
- [pyfolio](https://github.com/quantopian/pyfolio) - Portfolio analytics and risk tear sheets.
- [QuantStats](https://github.com/ranaroussi/quantstats) - Portfolio analytics with HTML/PDF reports.

## Order Flow & Market Microstructure

- [GFIL Terminal](https://gfil-intel.xyz) - Browser-based WebSocket terminal with cumulative delta, volume profile, footprint charts. Sub-50ms data for 30+ instruments. Free, no broker account required.
- [Stoikov Microstructure](https://github.com/sstoikov/microstructure) - Market microstructure research code.
- [LOBSTER](https://lobsterdata.com/) - Limit order book data for academic research.

## Machine Learning for Trading

- [FinRL](https://github.com/AI4Finance-Foundation/FinRL) - Deep RL for automated stock trading.
- [QLib](https://github.com/microsoft/qlib) - Microsoft's AI-oriented quantitative investment platform.
- [TradingML](https://github.com/topics/trading-machine-learning) - GitHub topic: ML for trading.
- [sktime](https://github.com/sktime/sktime) - Time series machine learning framework.

## Forex Trading

- [gfil-trading-calculators](https://github.com/liudapao880807-arch/gfil-trading-calculators) - Pip value calculator, position size for 30+ forex pairs, cross-pair conversion.
- [ForexConnect](https://github.com/nickgash/ForexConnect) - ForexConnect API wrapper.
- [OANDA v20 REST API](https://github.com/oanda/v20-python) - Official OANDA v20 Python wrapper.

## Gold & Commodities

- [gfil-trading-calculators](https://github.com/liudapao880807-arch/gfil-trading-calculators) - XAUUSD-specific calculators: gold pip value ($0.01/tick), gold position size, gold risk calculator, gold price prediction.
- [COMEX Data](https://www.cmegroup.com/market-data/) - CME Group market data for gold, silver, and other commodities.
- [CFTC COT Reports](https://www.cftc.gov/MarketReports/CommitmentsofTraders) - Commitments of Traders reports for gold and other commodities.

## Crypto Trading

- [Freqtrade](https://github.com/freqtrade/freqtrade) - Crypto trading bot.
- [Hummingbot](https://github.com/hummingbot/hummingbot) - Market making bot.
- [ccxt](https://github.com/ccxt/ccxt) - Unified crypto exchange API.
- [Jesse](https://github.com/jesse-ai/jesse) - Crypto backtesting and research.

## Datasets

- [Dukascopy Forex Data](https://www.dukascopy.com/swiss/english/marketwatch/historical/) - Free tick-level forex data (1999–present).
- [Kaggle Forex Datasets](https://www.kaggle.com/datasets?search=forex) - Community forex datasets.
- [Kaggle Gold Datasets](https://www.kaggle.com/datasets?search=gold+price) - Community gold price datasets.
- [CFTC COT Data](https://www.cftc.gov/MarketReports/CommitmentsofTraders) - Weekly COT reports.
- [Federal Reserve FRED](https://fred.stlouisfed.org/) - Economic data: interest rates, CPI, GDP, gold reserves.

## Educational Resources

- [QuantConnect](https://www.quantconnect.com/learn) - Free algorithmic trading courses.
- [Investopedia](https://www.investopedia.com/) - Comprehensive financial education.
- [BabyPips](https://www.babypips.com/) - Free forex trading education for beginners.
- [GFIL Blog](https://blog.quant-view.xyz/) - Trading calculators, research reports, and educational content in 4 languages.
- [OpenAI Trading Papers](https://github.com/topics/algorithmic-trading) - GitHub topic for algorithmic trading research.

## Community & Forums

- [r/algotrading](https://www.reddit.com/r/algotrading/) - Reddit community for algorithmic trading.
- [r/Daytrading](https://www.reddit.com/r/Daytrading/) - Reddit community for day trading.
- [QuantConnect Community](https://www.quantconnect.com/forum) - Algorithmic trading forum.
- [Elite Trader](https://www.elitetrader.com/) - Active trading forum.
- [GFIL Telegram](https://t.me/GFIL_Trading) - Trading community on Telegram.

---

## Contributing

Contributions are welcome! Please follow these guidelines:

1. **One resource per PR** — makes review faster.
2. **Add to the appropriate section** — if no section fits, suggest a new one.
3. **Format**: `- [Name](URL) - Brief description.`
4. **Description should be concise** — 1-2 sentences max.
5. **No affiliate links** — only direct links to open-source or free resources.
6. **Alphabetical order** within each section.

---

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the contributors have waived all copyright and related rights to this work.
