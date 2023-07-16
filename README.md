# Stock Market Analysis and Prediction

This project analyzes stock market data and utilizes a GRU (Gated Recurrent Unit) model for forecasting stock prices.

Stock market dataset (2006 - 2018) of [Amazon](https://www.amazon.com), [Google](https://www.google.com), [Microsoft](https://www.microsoft.com) & [IBM](https://www.ibm.com)

### Code Overview

### EDA (Exploratory Data Analysis)

The EDA section of the project focuses on analyzing the data and understanding the stock market trends. It includes data visualization using various libraries such as `numpy`, `pandas`, `matplotlib`, `seaborn`, and `plotly.express`. The key steps in the EDA process include:

- Importing necessary libraries and loading stock market data for companies like Google, Microsoft, Amazon, and IBM.
- Performing data exploration and descriptive statistics using functions like `head()`, `describe()`, and `info()`.
- Visualizing data using histograms, scatter plots, line plots, and seasonal decomposition.
- Analyzing trends and seasonality in stock prices.

### Modelling

The Modelling section of the project focuses on building a GRU (Gated Recurrent Unit) model for stock price forecasting. The key steps in this section include:

- Preprocessing the data by normalizing the stock prices using `MinMaxScaler` and splitting it into training and testing sets.
- Defining the GRU model architecture using the `nn.GRU` class from the `torch.nn` module.
- Training the GRU model using the training data and calculating the mean squared error loss.
- Making predictions using the trained model and visualizing the results.

### Additional Data Visualization

The Additional Data Visualization section includes additional visualizations of stock prices using libraries like `matplotlib` and `seaborn`. It provides insights into the stock price trends over time for companies like Amazon, Google, IBM, and Microsoft.

## Requirements

- Python 3.x
- numpy
- pandas
- matplotlib
- seaborn
- plotly
- torch

## Usage

To use this code, follow these steps:

1. Install the required dependencies mentioned in the Prerequisites section.

2. Download the stock market data for companies like Google, Microsoft, Amazon, and IBM. Make sure the data files are in CSV format and follow the same structure as the provided examples.

3. Update the file paths in the code to point to the respective data files for each company.

4. Modify the code as needed to customize the lookback window, model architecture, and other parameters.

5. Run the code and observe the results. The program will perform EDA, train the GRU model, and generate visualizations for analysis and forecasting.

Feel free to experiment with different data, model architectures, and parameters to explore the stock market analysis and forecasting capabilities of the GRU Time Series model.
