# Multi-API Data Extractor: Pokémon, Harry Potter, Crypto & Stock Market Insights

This Python project demonstrates how to fetch, parse, and display structured data from multiple popular public APIs, covering diverse domains such as gaming, entertainment, cryptocurrency, and finance.

---

## Features

- **Pokémon Data**  
  Fetch detailed Pokémon information like abilities, types, height, weight, and base experience using the [PokéAPI](https://pokeapi.co/).

- **Harry Potter Characters**  
  Collect rich character data, including wand details, Hogwarts affiliation, actor info, and more from the [Harry Potter API](https://hp-api.onrender.com/).

- **Cryptocurrency Prices**  
  Retrieve real-time cryptocurrency prices (BTC, ETH, DOGE, SOL, SHIB) in USD and EUR from the [CryptoCompare API](https://min-api.cryptocompare.com/).

- **Stock Market Financials**  
  Pull quarterly financial reports (balance sheet, income statement, cash flow) and company info for popular stocks like Apple, Microsoft, Tesla, Google, etc., using the [Yahoo Finance Python SDK (yfinance)](https://github.com/ranaroussi/yfinance).

---

## Technologies & Libraries

- Python 3.x  
- `requests` — for API calls  
- `pandas` — for data manipulation and CSV export  
- `tabulate` — for pretty-printing tables in console  
- `tqdm` — progress bars for loops  
- `yfinance` — stock market data extraction  

---


## Example Output

```
Pokémon Information for 'Charizard':

+------------------+------------+
| Attribute        | Value      |
+==================+============+
| Name             | Charizard  |
| Height           | 17         |
| Weight           | 905        |
| Base Experience  | 240        |
| Abilities        | blaze, solar-power |
| Types            | fire, flying |
+------------------+------------+

Company: Apple Inc.
Sector: Technology
Country: United States
Market Cap: $2,345,000,000,000
Current Price: $145.09
