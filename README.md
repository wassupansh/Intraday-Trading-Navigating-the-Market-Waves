# Intraday-Trading-Navigating-the-Market-Waves

This project focuses on developing an automated intraday trading system that provides buy and sell signals by leveraging real-time data from the Kite-Zerodha trading platform. It combines technical analysis with sentiment analysis to identify potential trading opportunities, aiming to optimize trading decisions and maximize profits

# Key Components
* Integrates with the Kite-Zerodha API to continuously extract real-time stock market data, including prices, volumes, and other indicators.

* Technical Analysis: Uses a combination of technical indicators (e.g., moving averages, RSI, MACD) to detect trends and potential reversal points.

* Incorporates news sentiment analysis related to SBIN (State Bank of India), analyzing news articles. Employs a transformer-based model to quantify market sentiment as positive, neutral, or negative.

* Uses a Random Forest Classifier to pinpoint the most influential features that drive market movements, achieving an impressive F1 score of 94%.

* Backtesting results are visualized to provide insights into the potential profitability and associated risks of different trading strategies.

* Generates automated buy and sell signals based on a blend of technical and sentiment analysis.
