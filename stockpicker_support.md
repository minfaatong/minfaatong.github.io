Stock Picker - User Support Guide
Welcome to Stock Picker! This guide will help you get the most out of the app.

📱 Getting Started
First Launch
Enter a Stock Symbol: Type a stock ticker (e.g., AAPL, MSFT, GOOGL) in the search field
Tap "Analyze": The app will fetch data and perform technical analysis
View Results: Toggle between "Analysis" and "Chart" tabs to see different insights
Quick Actions
Recent Symbols: Tap the quick symbol buttons below the search bar to reload previously analyzed stocks
Search & Import: Use the "Search & Import" button to browse or import CSV files
History: Access your analysis history via the history icon (📜) in the top-right
⚙️ Settings
Access settings by tapping the ⚙️ icon in the top-right corner.

Trading Strategy
Choose from 15+ technical analysis strategies:

Trend Confirmation Composite: Best for identifying strong uptrends
Reversal Confirmation Composite: Detects potential trend reversals
MACD Crossover: Classic momentum indicator
RSI Divergence: Identifies overbought/oversold conditions
And many more...
Timeframe
Select the data granularity:

Intraday: Minute-by-minute data (requires premium API)
Daily: End-of-day prices (recommended)
Weekly: Week-ending prices
Monthly: Month-ending prices
Analysis Period
Choose how much historical data to analyze:

1D, 5D: Short-term (intraday trading)
1mo, 6mo: Medium-term (swing trading)
YTD, 1y, 5y: Long-term (position trading)
API Configuration
Alpha Vantage API Key
The app uses Alpha Vantage for stock data.

Default Key Limitations:

25 requests per day (free tier)
Shared among all users using the default key
Get Your Own API Key (Recommended):

Click the ? icon next to the API Key field
Visit: https://www.alphavantage.co/support/#api-key
Fill in your information and get a free API key
Paste your API key in the settings
Enjoy 25 requests per day on YOUR OWN quota
Premium Plans Available:

Higher request limits
Real-time data
More features
Chart Options
Moving Averages
Default: Shows 20-day and 50-day moving averages
Toggle ON: Adds 10-day moving average (purple line)
Use Case: Identify short-term vs long-term trends
Support Lines
Green dashed line: Lowest price in the current period
Use Case: Identify potential bounce points
Resistance Lines
Red dashed line: Highest price in the current period
Use Case: Identify potential selling zones
Volume Bars
Gray bars: Trading volume over time
Use Case: Confirm price movements with volume
Trend Channel (Auto-Detection)
ON by default: Automatically detects trend patterns
Ascending Channel: Cyan lines indicate uptrend
Descending Channel: Orange lines indicate downtrend
Requirements:
Minimum 10 data points
Strong correlation (>60%)
Parallel lines (within 15% slope difference)
Use Case: Identify clear trending patterns for channel trading
📊 Understanding the Chart
Chart Type
Candlestick Chart: Shows OHLC (Open, High, Low, Close) data
Green candles: Close > Open (bullish)
Red candles: Close < Open (bearish)
Chart Lines & Colors
Line/Indicator	Color	Description
Close Price	Light Blue (subtle)	Connects closing prices
20MA	Orange	20-day moving average
50MA	Red	50-day moving average
200MA	Brown	200-day moving average
10MA (optional)	Purple	10-day moving average
Support	Green (dashed)	Lowest low in period
Resistance	Red (dashed)	Highest high in period
Uptrend Channel	Cyan (dashed)	Ascending channel lines
Downtrend Channel	Orange (dashed)	Descending channel lines
Interactive Tooltips
Tap or hover on the chart to see detailed information:

2025-08-13
Close: $203.03
200MA: $183.59
50MA: $189.45
20MA: $194.95
10MA: $197.90
Support: $175.50
Resistance: $210.25
Legend
The chart legend at the top shows which indicators are currently visible.

🔍 Analysis Tab
Confidence Score
0-100%: How confident the algorithm is in its recommendation
Color coded:
Green: Strong Buy/Buy
Yellow: Hold/Wait
Red: Sell/Strong Sell
Decision Types
Strong Buy: Excellent entry opportunity
Buy: Good entry opportunity
Hold: Maintain current position
Wait: Unclear signal, wait for confirmation
Sell: Consider exiting
Strong Sell: Strong exit signal
Key Indicators
The analysis shows relevant technical indicators based on the selected strategy:

Moving Averages
RSI (Relative Strength Index)
MACD
Volume trends
Support/Resistance levels
💡 Tips & Best Practices
For Best Results
Use your own API key to avoid hitting daily limits
Match strategy to timeframe:
Short-term strategies → 1D to 1mo
Long-term strategies → YTD to 5y
Check multiple timeframes for confirmation
Enable trend channels to spot clear patterns
Compare volume with price movements
Trading Insights
Using Trend Channels
Buy near lower channel line in uptrend
Sell near upper channel line in uptrend
Short near upper line in downtrend
Cover near lower line in downtrend
Watch for breakouts above/below channel
Moving Average Crossovers
Golden Cross: 20MA crosses above 50MA (bullish)
Death Cross: 20MA crosses below 50MA (bearish)
200MA: Major long-term support/resistance
Support & Resistance
Price bounces off support: Potential buy opportunity
Price rejected at resistance: Potential sell opportunity
Breakout above resistance: Strong bullish signal
Breakdown below support: Strong bearish signal
🎯 Common Use Cases
Day Trading
Set timeframe to Daily or Intraday
Set period to 1D or 5D
Use short-term strategies (RSI, Stochastic, MACD)
Enable all chart options for maximum information
Watch for trend channel breakouts
Swing Trading
Set timeframe to Daily
Set period to 1mo or 6mo
Use mid-term strategies (Trend Confirmation, MACD Crossover)
Focus on moving average crossovers
Trade within trend channels
Long-Term Investing
Set timeframe to Weekly or Monthly
Set period to 1y or 5y
Use long-term strategies (Primary Trend Filter)
Watch the 200MA for major trend direction
Buy on support, sell on resistance
🌟 Premium Features
In-App Purchases
Tap the ⭐ icon to:

Remove ads
Support development
Get premium features (coming soon)
❓ Troubleshooting
"Failed to load data"
Check API key: Make sure it's valid
Daily limit reached: Wait 24 hours or upgrade API plan
Invalid symbol: Verify the stock ticker is correct
Network issue: Check your internet connection
Chart not showing
Make sure you've successfully loaded data
Toggle to "Chart" tab
Check that chart options are enabled in settings
Slow performance
Reduce analysis period (use 1mo instead of 5y)
Disable unnecessary chart options
Close and restart the app
📧 Support
For additional help:

Documentation: Check the README.md file
Issues: Report bugs on GitHub (if open source)
Email: Contact the developer
🔄 Updates
This app is regularly updated with:

New trading strategies
Improved algorithms
Bug fixes
UI enhancements
Keep your app updated for the best experience!

Version: 1.0
Last Updated: 2025

Happy Trading! 📈🚀
