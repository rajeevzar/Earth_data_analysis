# Environmental Health Analysis by Country

This project provides tools for analyzing and visualizing environmental health data by country using datasets from [NASA Earthdata](https://search.earthdata.nasa.gov/search). 
The focus is on air quality indices and other environmental indicators, such as PMD (Particulate Matter 2.5), OZD (Ozone Exposure), and REC (Recycling Rate).

---

## Features
### 1. Scatter Plot for Median Environmental Indicators
- Visualize the median environmental index (e.g., PMD, OZD) for each country.
- Categorize data into "Good," "Moderate," and "Severe" levels based on thresholds.
- Interactive scatter plot with Plotly.

### 2. Time Series Analysis
- Analyze year-wise trends of any environmental indicator for a specific country.
- Visualize time series data dynamically with Plotly.

---

## Dependencies
The code requires the following Python libraries:
- `pandas`
- `numpy`
- `plotly`

Install them via:
```bash
pip install pandas numpy plotly
