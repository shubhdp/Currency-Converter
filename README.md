# Currency Converter

This project is a simple **Currency Converter** web application that allows users to convert one currency to another using real-time exchange rates. The app is built using **HTML**, **CSS**, and **JavaScript**, and it fetches exchange rates from a public API. The app also dynamically updates country flags based on the selected currencies.

## Features

- Real-time currency exchange rates.
- Default currencies: **USD** (from) and **INR** (to).
- Dynamically populated currency dropdown menus.
- Automatic updating of country flags for selected currencies.
- Handles user input validation for currency amounts.

## Technologies Used

- **HTML**: Structuring the webpage.
- **CSS**: Styling the user interface.
- **JavaScript**: Handling API calls, DOM manipulation, and currency conversion logic.
- **Currency API**: [Currency API by Fawaz Ahmed](https://github.com/fawazahmed0/currency-api) for fetching exchange rates.
- **Flags API**: To display country flags based on selected currencies.

## Files

- `index.html`: The main webpage containing the structure and layout.
- `style.css`: The stylesheet that provides the design and layout.
- `app.js`: The main JavaScript file for handling logic such as fetching exchange rates and updating the UI.
- `codes.js`: The file containing the list of currency codes and their respective country codes.

## How to Use

1. Enter an amount in the input field (defaults to 1).
2. Select the currencies you want to convert from and to.
3. Click the "Get Exchange Rate" button to see the converted amount.
4. The result is displayed along with the conversion rate and the relevant country flags.

## How to Run

1. Clone the repository.
2. Open the `index.html` file in your browser.
3. The app should load, showing default exchange rates from **USD to INR**.
4. Select different currencies and amounts as desired.
