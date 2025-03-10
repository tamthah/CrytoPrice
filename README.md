# Crypto Price App

## Overview
The **Crypto Price App** is a simple web application that fetches real-time cryptocurrency prices using the [CoinGecko API](https://www.coingecko.com/en/api/documentation) and displays them in a visually appealing format. The app shows the current price of popular cryptocurrencies along with their 24-hour price change.

## Features
- Fetches real-time cryptocurrency prices.
- Displays Bitcoin, Ethereum, Litecoin, Cardano, Dogecoin, and Tether prices.
- Highlights price increases and decreases using colors.
- Simple and clean UI with CSS animations.

## Technologies Used
- **HTML** - Structuring the web page.
- **CSS** - Styling and layout.
- **JavaScript (Fetch API)** - Fetching live data from CoinGecko API.

## Setup & Usage
### 1. Clone the Repository
```sh
git clone https://github.com/yourusername/crypto-price-app.git
cd crypto-price-app
```

### 2. Open the `index.html` File
Simply open `index.html` in a browser, and the app will fetch live cryptocurrency prices.

### 3. Ensure Internet Access
Since the app relies on fetching data from an external API, make sure you have an active internet connection.

## API Information
- **Endpoint Used:**
  ```sh
  https://api.coingecko.com/api/v3/simple/price?ids=bitcoin%2Ctether%2Cethereum%2Clitecoin%2Ccardano%2Cdogecoin&vs_currencies=usd&include_24hr_change=true
  ```
- **Data Provided:**
  - USD price of each cryptocurrency
  - 24-hour percentage change in price

## Screenshot
![Crypto Price App](images/demo.png) *(Add an actual screenshot here)*

## Future Improvements
- Add more cryptocurrencies.
- Implement a search feature.
- Use WebSockets for real-time updates.
- Improve UI with additional animations.

## License
This project is licensed under the **MIT License**.

## Author
Developed by **[Your Name]** (Replace with your actual name).