# Green ETF Analysis

The Green ETF Analysis project aims to compare and contrast several major green ETFs with each other and with the Vanguard Total Stock Market ETF (VTI). The analysis includes visualizations of adjusted close values, moving averages, daily returns, and value at risk assessments.

The ETFs analyzed are:

- **iShares Global Clean Energy ETF (ICLN)**: 
        -Total assets: $2.477 billion
- **First Trust NASDAQ Clean Edge Green Energy Index Fund (QCLN)**:
        -Total assets: $837.32 million
- **Invesco WilderHill Clean Energy ETF (PBW)**:
        -Total assets: $366.32 million
- **ALPS Clean Energy ETF (ACES)**:
        -Total assets: $230.22 million
- **SPDR S&P Kensho Clean Power ETF (CNRG)**:
        -Total assets: $213.84 million

## Requirements

- Python 3.x
- numpy
- pandas
- matplotlib
- seaborn
- yfinance
- scipy

You can install the required libraries using pip:

```bash
pip install numpy pandas matplotlib seaborn yfinance scipy
```

## Usage

### Clone or Download the Notebook:
You can clone the repository or download the notebook directly.

### Open the Notebook:
Use Jupyter Notebook or JupyterLab to open the notebook file (.ipynb).

```bash
jupyter notebook green_ETF_analysis.ipynb
```

### Execute Cells:
Run each cell in the notebook sequentially to perform the analysis.

## Analysis Sections

1. **Data Acquisition**:
The notebook fetches historical data for the ETFs and VTI using the yfinance library for the past year.
2. **Adjusted Close Values**:
Visualizations of historical adjusted close values for each ETF.
3. **Moving Averages**:
Plots showing the 10, 20, and 50-day moving averages for each ETF.
4. **Daily Returns**:
Histograms and KDE plots of daily returns for each ETF.
5. **Correlation Analysis**:
Pairplots and heatmaps to visualize correlations between adjusted close values and daily returns of the ETFs.
6. **Value at Risk (VaR)**:
    - **Quantile Method**: Calculation of VaR using quantiles to estimate potential risk.
    - **Monte Carlo Simulation**: Simulation of future price distributions to estimate potential risk and price distributions.
