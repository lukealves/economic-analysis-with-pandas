# Economic Data Analysis with Fred & Pandas

This is a project that demonstrates how to use Python, Pandas, and the Federal Reserve Economic Data (FRED) API to download and analyze economic data. The goal of this project is to show how to retrieve data from FRED, visualize it using Pandas, and discover insights from it.

# Requirements

- `Python 3.7` or higher
- `Pandas`
- `Numpy`
- `Matplotlib`
- `Plotly`
- `fredapi` (available on `PyPI`)
- A `FRED API` key (you can get one for free from the FRED website)

# Setup

1. Clone this repository to your local machine
2. Install the requirements listed above using pip (e.g. `pip install pandas`)
3. Replace the `'put_your_key_here'` placeholder with your FRED API key
4. Run the Jupyter notebook `economic_data_analysis.ipynb`

# Usage

The notebook includes several sections that demonstrate different ways of working with economic data. Here's a brief summary of each section:

1. Importing libraries and setting options: This section imports the necessary Python libraries and sets some display options for Pandas.
2. Creating the FRED object: This section creates a `Fred` object from the `fredapi` library and sets the API key.
3. Searching for economic data: This section demonstrates how to `search` for economic data using the search method of the `Fred` object. It also shows how to filter the search results and get some basic information about the data.
4. Pulling raw data and plotting: This section shows how to download raw data from FRED using the `get_series` method of the `Fred` object and plot it using Matplotlib.
5. Pulling and joining multiple data series: This section demonstrates how to download and join multiple data series using the FRED API and Pandas. It also shows how to clean up the resulting DataFrame and plot the data using Plotly.
6. Pulling April 2020 unemployment rate per state: This section pulls the unemployment rate for each US state in April 2020, sorts the states by unemployment rate, and plots the results using Matplotlib.


# Credits
This project was created for study purposes and not for any commercial use. It is based on the **fredapi documentation** and uses data from the Federal **Reserve Economic Data (FRED)**.
