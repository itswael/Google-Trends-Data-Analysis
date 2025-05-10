# Google Trends Data Analysis

This project explores the relationship between Google search trends and various real-world data, such as stock prices and unemployment rates. Using Python and data visualization libraries, we analyze datasets to uncover patterns and insights.

## Data Sources

The following data sources are used in this project:

- [Unemployment Rate from FRED](https://fred.stlouisfed.org/series/UNRATE/)
- [Google Trends](https://trends.google.com/trends/explore)
- [Yahoo Finance for Tesla Stock Price](https://finance.yahoo.com/quote/TSLA/history?p=TSLA)
- [Yahoo Finance for Bitcoin Stock Price](https://finance.yahoo.com/quote/BTC-USD/history?p=BTC-USD)

## Project Structure

- **`Google Trends and Data Visualisation.ipynb`**: The main Jupyter Notebook containing the code for data analysis and visualization.
- **`TESLA Search Trend vs Price.csv`**: Tesla search trend and stock price data.
- **`Bitcoin Search Trend.csv`**: Bitcoin search trend data.
- **`Daily Bitcoin Price.csv`**: Daily Bitcoin price data.
- **`UE Benefits Search vs UE Rate 2004-19.csv`**: Unemployment benefits search trends and unemployment rate data (2004-2019).
- **`UE Benefits Search vs UE Rate 2004-20.csv`**: Unemployment benefits search trends and unemployment rate data (2004-2020).

## Key Features

### 1. Data Cleaning
- Handle missing values in datasets.
- Convert date columns to Pandas `Datetime` objects for easier time-series analysis.

### 2. Data Exploration
- Analyze the shape, column names, and descriptive statistics of the datasets.
- Identify trends and patterns in search data and real-world metrics.

### 3. Data Visualization
- **Tesla Stock Price vs Search Volume**: Visualize Tesla's stock price against its search popularity using dual-axis line charts.
- **Bitcoin Price vs Search Volume**: Compare Bitcoin's price with its search volume, using markers and line styles to highlight trends.
- **Unemployment Benefits Search vs Unemployment Rate**: Analyze the relationship between search trends for unemployment benefits and the actual unemployment rate.
- **Rolling Averages**: Calculate and visualize rolling averages for smoother trend analysis.

### 4. Including 2020 Data
- Extend the unemployment analysis to include 2020 data for a more comprehensive view.

## Libraries Used

- `pandas`: For data manipulation and analysis.
- `matplotlib`: For creating visualizations.
- `matplotlib.dates`: For formatting date-based visualizations.

## How to Run

1. Clone this repository and navigate to the project folder.
2. Ensure all `.csv` files are in the same directory as the Jupyter Notebook.
3. Install the required Python libraries:
   ```bash
   pip install pandas matplotlib