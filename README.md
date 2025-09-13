# Historical Stock Analysis of Top Tech Companies
A Python project to extract and analyze historical stock data for top tech companies using pandas and yfinance.

## Description

This project demonstrates a complete data science workflow for extracting and analyzing financial data. It focuses on gathering historical stock performance and revenue data for major technology companies, specifically Tesla (TSLA) and GameStop (GME). The project involves fetching data directly from APIs using the `yfinance` library and scraping data from web pages using `BeautifulSoup`. The extracted data is then cleaned, processed, and prepared for analysis using the `pandas` library.

## Technologies Used

* **Python 3**
* **Jupyter Notebook**
* **Pandas:** For data manipulation and analysis.
* **yfinance:** For extracting historical stock market data.
* **Requests:** For making HTTP requests to websites.
* **BeautifulSoup4:** For web scraping and parsing HTML.
* **Plotly:** For creating interactive data visualizations (or Matplotlib/Seaborn if used).

## Features

* Extracts historical stock data (Open, High, Low, Close, Volume) for any given ticker using the `yfinance` library.
* Scrapes quarterly revenue data from web pages using `BeautifulSoup`.
* Cleans and preprocesses the extracted data, including removing currency symbols, handling missing values, and ensuring correct data types.
* Stores the cleaned data in a structured pandas DataFrame.
* (Optional) Visualizes the stock performance and revenue trends over time.

## How to Run

1.  Clone this repository to your local machine:
    ```bash
    git clone [https://github.com/YOUR_USERNAME/tech-stock-analysis.git](https://github.com/YOUR_USERNAME/tech-stock-analysis.git)
    ```
2.  Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```
    *(Note: You may need to create a `requirements.txt` file listing the libraries above.)*

3.  Open and run the Jupyter Notebook (`.ipynb`) file to see the full analysis.
