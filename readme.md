# TradingView Watchlist API Manipulation (Educational Purpose Only) #

**!!! Warning !!!**  
This code is intended for educational purposes only. It interacts with a premium feature of the [TradingView](https://in.tradingview.com/) application. Please refrain from using it for personal or commercial purposes.

## Overview

This Jupyter notebook demonstrates how to interact with the TradingView's own API to manipulate watchlists. The notebook covers the following operations:

1. **Retrieving a Watchlist**: Fetch the current list of symbols in a specified TradingView watchlist.
2. **Clearing a Watchlist**: Remove all symbols from a specified TradingView watchlist.
3. **Appending to a Watchlist**: Add new symbols to a specified TradingView watchlist.

## Prerequisites

- **Jupyter Notebook** or any compatible environment to run `.ipynb` files.
- **Requests Library**: Used to make HTTP requests to the TradingView's API.

  You can install the requests library using pip:

  ```bash
  pip install requests
  ```

## Setup

1. **Clone the Repository**  
   Clone this repository to your local machine:

   ```bash
   https://github.com/Amysoj-Louis/TradingView-Watchlist-API-Manipulation
   ```

2. **Session and Watchlist IDs**  
   To use the API, you'll need to extract your `session_id` and `watchlist_id`:

   - **Session ID**: Obtain this from the cookies in your browser when logged into TradingView. It's a 32-character alphanumeric string.
   - **Watchlist ID**: Extract this from the URL when you access a specific watchlist in TradingView. It's an 8-character alphanumeric string.

3. **Update the Notebook**  
   Open the notebook and update the following variables:

   ```python
   session_id = "your_session_id_here"
   watchlist_id = "your_watchlist_id_here"
   ```

## How to Use

### 1. Retrieve Watchlist

The notebook fetches the current symbols in your TradingView watchlist:

### 2. Clear Watchlist

This section is used to clear all symbols from your TradingView watchlist:

### 3. Append to Watchlist

Allows you to add a predefined list of symbols to your TradingView watchlist:

### Stocklist

You can modify the `Stocklist` variable with your preferred stocks:

```python
Stocklist = ['RELIANCE', 'TCS', 'HDFCBANK', 'INFY', 'ICICIBANK', 'HINDUNILVR']
```

## Important Notice

- **Educational Use Only**: This code is intended for educational purposes to demonstrate API interactions. Using it for personal or commercial purposes may violate TradingView’s terms of service.

## Disclaimer

The author is not responsible for any misuse of this code. Use at your own risk.


---

### Update: TradingView Free Plan Limitations
- Users on premium plans can manually adjust this limit according to their subscription. However, users on the free plan will not be able to bypass this restriction through the script.
