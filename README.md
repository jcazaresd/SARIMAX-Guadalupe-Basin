# SARIMAX-Guadalupe-Basin
# Hydrometeorological Reconstruction Through Basin Morphometric Characterization and Autoregressive Precipitation Modeling: Linking Static Form and Dynamic Signals

This repository contains the official Python implementation and methodological workflow developed as supplementary material for the manuscript under review in Hydrology and Earth System Sciences (2026). Authors: Cazares-Duran, J.J., Aguilar-Ojeda, J. A., & Kretzschmar, T.

The provided Jupyter Notebook contains a complete workflow applied to analyze, model, and impute hydrometeorological time series. It utilizes linear time-series frameworks, specifically AutoRegressive Integrated Moving Average (ARIMA) and Seasonal AutoRegressive Integrated Moving Average with Exogenous Regressors (SARIMAX). These models are designed to capture temporal structures, seasonal periodicities, and external forcings within a specific study area context.

## Repository Structure and Data

To successfully replicate the methodology, the following structure should be maintained:
- `SARIMAX_Guadalupe_Basin.ipynb`: The main workflow notebook containing code, visualizations, and modeling steps.
- `data/Rain_gauges_mm.csv`: The required input dataset containing the rain gauge structure and historical precipitation station network metadata (covering the period 1980–2020).

## Prerequisites and Installation

The source code was built using Python 3.10.19 (packaged by Anaconda, Inc.). To setup the local environment and install all necessary main dependencies (including statsmodels, geopandas, astropy, and contextily), execute the following command in your terminal:

```bash
pip install -r requirements.txt
