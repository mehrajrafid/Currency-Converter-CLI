# Currency Converter CLI

A simple and interactive command-line interface (CLI) application that allows users to convert currencies using real-time exchange rates fetched from the [ExchangeRate-API](https://www.exchangerate-api.com).

---

## Features

- Converts between over **150+ currencies**.
- Fetches real-time exchange rates from the ExchangeRate-API.
- Provides a simple and user-friendly CLI interface.
- Error handling for unsupported currencies and invalid inputs.

---

## Prerequisites

Ensure you have the following installed on your system:
- Python 3.8 or higher
- `requests` library (for fetching exchange rates)

Install the required library by running:
bash
pip install requests

# How to Use
Clone the repository or download the script.
Open a terminal and navigate to the directory where the script is saved.
Run the script:
python currency_converter.py

4. Follow the prompts to:
Enter the currency you want to convert from (e.g., USD).
Enter the currency you want to convert to (e.g., EUR).
Enter the amount to convert.

# Example
Input:
Welcome to Currency Converter CLI!
Fetching latest exchange rates...

Available currencies: USD, EUR, GBP, INR, JPY, AUD, CAD, ...

Enter the currency you want to convert from (e.g., USD): USD
Enter the currency you want to convert to (e.g., EUR): EUR
Enter the amount in USD: 100

Output:
💱 200.00 USD = 24397.77 BDT

# API Used
This project uses the ExchangeRate-API, which provides free and real-time exchange rates.

# Example API Call:
https://open.er-api.com/v6/latest/USD

#API response
{
  "result": "success",
  "provider": "https://www.exchangerate-api.com",
  "base_code": "USD",
  "rates": {
    "USD": 1,
    "EUR": 0.9438,
    "GBP": 0.802,
    "INR": 86.36,
    ...
  }
}

# Future Improvements
Add support for historical exchange rates.
Implement a graphical user interface (GUI) for easier interaction.
Allow batch conversion for multiple currencies at once.

# Contributing
Contributions are welcome! Feel free to fork this repository and submit a pull request with your improvements or suggestions.
# License
This project is licensed under the MIT License. See the LICENSE file for details.

Enjoy using the Currency Converter CLI! 🌍💱
