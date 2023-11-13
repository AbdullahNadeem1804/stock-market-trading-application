# Stock Market Trading Simulator Application
A stock market trading application which uses concepts of c++ including Read from file, using 2-D array, iomanip, functions, loops, arrays(search also), strings, random numbers and function to convert string to float.

# 'Karachi' Stock Market Trading Simulator

## Project Overview

For my final project in Programming Fundamentals, I have developed a simulator of a stock market trading application using C++. This application follows a set of functionalities to mimic the dynamics of a live stock market session.

### Load/Save Stock Market Data

To initiate the simulation, the program reads data from the `companies.txt` file and stores it in a 2-D array. Each line in the file consists of comma-separated values representing stock symbol, company name, and current price. Upon closing the application, the updated stock prices are saved back to the file.

Key C++ concepts used: Reading from a file, using a 2-D array.

### Show Stock Market Screen

The live stock market screen displays information about various stocks, including their symbol, company name, offer price, high and low values for the current session. The offer prices fluctuate randomly but within a 15% increase or decrease cap. The application keeps track of shares bought and sold during the session, calculates the percentage of price changes, and identifies the top advancer and decliner.

C++ concepts used: iomanip, functions, loops, arrays, strings, random numbers.

### User Portfolio

Users can create and manage their portfolios, which include a collection of shares from different companies. The portfolio screen displays the user's account balance, any profit or loss, and details of each stock in the portfolio. Users can add or remove stocks, add or withdraw money from their accounts, and switch between the live market and portfolio screens.

Key C++ concepts used: Read from/write to file (for portfolio data), iomanip for formatting.

### Load/Store User Portfolio

Upon the first run, the program prompts users to enter portfolio data, which is displayed and stored in the `portfolio.txt` file when the program ends.

C++ concepts used: Read from/write to file.

### Show Portfolio Screen

Similar to the main market screen, the portfolio screen updates when the user presses ENTER, reflecting changes in stock values.

C++ concepts used: iomanip, functions, loops, arrays (search), strings.

### Add Stock to Portfolio

Users can add new stocks to their portfolios by specifying the number of shares to buy and the stock symbol. The program deducts the appropriate amount from the user's balance.

C++ concepts used: Functions, loops, arrays (search), strings.

### Remove Stock from Portfolio

Users can sell stocks from their portfolios by entering the stock symbol and the number of shares to sell. The program updates the user's balance accordingly.

C++ concepts used: Functions, loops, arrays (search), strings.

### Add/Withdraw Money

Users can add or withdraw money from their accounts, with appropriate validations to prevent actions such as withdrawing more money than the available balance.

C++ concepts used: Functions, loops, arrays (search).

---

This project encompasses various C++ concepts to create a comprehensive stock market trading simulator, providing users with an interactive and dynamic experience.
