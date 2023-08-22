# EDA-and-Stock-Analysis-with-Time-Series-Data

This project demonstrates how to perform stock data analysis using the Pandas library and visualize the results using Matplotlib. The analysis includes fetching stock data using the Yahoo Finance API, resampling, rolling averages, and plotting various aspects of the data.

## Getting Started

To run this project, you need to have the following libraries installed:

- Pandas
- yfinance (Yahoo Finance API)
- Matplotlib

You can install these libraries using the following commands:

```sh
pip install pandas
pip install yfinance
pip install matplotlib
```
<h2>Code Explanation</h2>
<h3>Fetching Stock Data</h3>
The code starts by importing necessary libraries and upgrading pandas_datareader and yfinance. It then fetches Tesla's stock data from Yahoo Finance using the yfinance library. The fetched data is stored in a Pandas DataFrame.

<h3>Resampling and Rolling Averages</h3>
The code demonstrates time resampling techniques like resampling by year, quarter, and business quarter start (BQS). It also calculates rolling averages (moving averages) using the rolling function.

<h3>Visualization</h3>
The code uses Matplotlib to visualize the stock data and analysis results. It plots various aspects of the data, such as opening prices, rolling averages, and resampled data.

<h3>How to Run</h3>
1) Install the required libraries using the commands provided above.<br>
2) Copy and paste the code into a Python environment or a Jupyter Notebook.<br>
3) Run the code cell by cell to see the output and visualizations.<br>
<h2>Contributing</h2>
If you'd like to contribute to this project, you can fork the repository, make your changes, and submit a pull request.
