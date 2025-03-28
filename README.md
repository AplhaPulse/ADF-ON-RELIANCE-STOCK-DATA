# Augmented Dickey-Fuller (ADF) Test Implementation

This repository provides a Python implementation of the Augmented Dickey-Fuller (ADF) test, a statistical test for time series stationarity.

**Purpose:**

Determines if a time series contains a unit root, indicating non-stationarity.
Non-stationary series have time-varying statistical properties (mean, variance).
Stationarity is required for many time series models.

**Implementation:**

Uses Python's statsmodels library (or a custom implementation) to perform the test.
Calculates the ADF test statistic and p-value.
Provides critical values for hypothesis testing.
Handles lag selection for accurate results.

**Usage:**

1.  Install dependencies (e.g., `pip install statsmodels numpy`).
2.  Input time series data.
3.  Run the `adfuller()` function (or provided equivalent).
4.  Interpret output:

    ```
    * Low p-value (e.g., < 0.05) indicates stationarity.
    * ADF stat lower than critical values also indicates stationarity.
    ```

**Key Concepts:**

Unit Root: A feature of non-stationary time series.
Lagged Differences: Used to account for autocorrelation.
Critical Values: Thresholds for statistical significance.

**Output:**

ADF test statistic.
p-value.
Critical values.
