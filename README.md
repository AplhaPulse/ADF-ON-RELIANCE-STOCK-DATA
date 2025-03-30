# Augmented Dickey-Fuller (ADF) Test on Reliance Stock Data

This repository contains a Python implementation of the Augmented Dickey-Fuller (ADF) test, used to assess the stationarity of Reliance Industries' stock price data.

## Description

The Augmented Dickey-Fuller (ADF) test is a statistical test used to determine if a time series is stationary or contains a unit root, indicating non-stationarity. Non-stationary series have time-varying statistical properties (mean, variance), which can hinder accurate forecasting. This repository demonstrates the use of the ADF test on Reliance Industries stock data.

## Installation

To run the code in this repository, you will need to install the following dependencies:

```sh
pip install numpy pandas matplotlib statsmodels pmdarima
```

## Usage

1. Clone the repository:
    ```sh
    git clone https://github.com/AplhaPulse/ADF-ON-RELIANCE-STOCK-DATA.git
    cd ADF-ON-RELIANCE-STOCK-DATA
    ```

2. Open the Jupyter Notebook file `ADF - Reliance.ipynb` to see the implementation.

### Key Steps in the Notebook

- **Install Required Packages:** Ensure all necessary libraries are available.
- **Import Libraries:** Load the essential Python libraries.
- **Load Dataset:** Import Reliance Industries stock data from an Excel file.
- **Plot Closing Prices:** Visualize the closing prices to identify trends.
- **Kernel Density Estimation Plot:** Assess the distribution of closing prices.
- **Check for Missing and Infinite Values:** Ensure data integrity.
- **Fill and Drop NaN Values:** Handle any missing values.
- **Test for Stationarity:** Apply the ADF test and interpret the results.

## Interpretation

- **Non-Stationary Series:** The series exhibits time-varying mean and variance, with a p-value greater than 0.05 and a test statistic exceeding critical values.
- **ADF Test Assumptions:**
  - **Null Hypothesis (H0):** The series is non-stationary (has a unit root).
  - **Alternate Hypothesis (H1):** The series is stationary (no unit root).
  - Rejecting H0 indicates stationarity, essential for reliable time series modeling.

## Contributing

Contributions are welcome! Please follow these steps to contribute:

1. Fork the repository.
2. Create a new branch:
    ```sh
    git checkout -b feature/your-feature
    ```
3. Make your changes and commit them:
    ```sh
    git commit -m 'Add some feature'
    ```
4. Push to the branch:
    ```sh
    git push origin feature/your-feature
    ```
5. Open a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
