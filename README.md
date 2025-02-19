# codealpha_task2
Developed stockportfolio project using python for codealpha internship
Stock Portfolio Management in Python
Overview
This Python project helps users manage and track their stock portfolio. The program allows users to add, remove, and view stocks in their portfolio, track the current value of their holdings, and calculate overall portfolio performance. The stock data is fetched using live stock market APIs to get real-time price updates for the stocks.

Features
Add Stocks: Users can add stocks to their portfolio by providing the stock symbol (e.g., AAPL for Apple, TSLA for Tesla), quantity, and purchase price.
Remove Stocks: Users can remove a stock from their portfolio.
View Portfolio: The user can view the current portfolio, including the number of stocks, the current market price, and the total value of each stock.
Track Stock Prices: The program fetches real-time stock prices using an API (such as Alpha Vantage or Yahoo Finance).
Portfolio Performance: It calculates the profit or loss on the stocks based on the difference between the current price and the purchase price.
Track Overall Portfolio Value: It shows the total value of the portfolio based on the current stock prices.
Stock History: Optionally, the program can track the historical performance of stocks.
Requirements
Python 3.x
requests library (for making HTTP requests)
pandas library (for organizing stock data)
yfinance or alpha_vantage (for fetching live stock data)
You can install the necessary libraries using pip:

bash
Copy
pip install requests pandas yfinance
Installation
Clone or download the repository to your local machine.

Navigate to the project directory:

bash
Copy
cd stock-portfolio
Install the necessary dependencies:

bash
Copy
pip install -r requirements.txt
You are now ready to run the application.

How to Use
Run the Portfolio Manager:

bash
Copy
python portfolio_manager.py
Menu Options: The user will be prompted with a menu of options to choose from, such as:

Add a stock to the portfolio
Remove a stock from the portfolio
View the portfolio
Track stock prices
Calculate portfolio performance
Input: You will be asked to input stock symbols (such as "AAPL" for Apple or "TSLA" for Tesla), the number of shares, and purchase prices. Stock prices will be fetched from a live market API.

View Portfolio: The program displays the stock holdings, their current values, and any profit or loss for each stock.

Exit: The user can exit the application at any time, and the portfolio data will be saved for later sessions.
