# QS Medicine Rankings and Pharmaceutical & Healthcare Stock Market Analysis

## Project Overview

This repository contains the Jupyter Notebook and supporting datasets for a master's-level data visualisation project examining the relationship between **QS World University Rankings by Subject – Medicine** and selected **pharmaceutical and healthcare stock-market data**.

The project combines university ranking data with stock-market data to explore country-level relationships, university performance patterns, stock-market behaviour, and similarities in company price movements.

The analysis covers QS Medicine rankings for **2024–2026** and stock-market data from **2010 to August 2026**.

## Research Questions

The project addresses the following research questions:

1. **RQ1:** Is pharmaceutical and healthcare sector stock-market performance associated with university performance in the QS WUR by Subject – Medicine across countries?
2. **RQ2:** What patterns and differences can be identified in QS Medicine performance across countries and ranking years?
3. **RQ3:** What patterns and differences can be identified in the stock-market performance of selected pharmaceutical and healthcare companies?
4. **RQ4:** How has Richter's stock-market performance evolved over time, and what key patterns can be identified in its stock price, returns and volatility based on visual representations?
5. **RQ5:** What similarities and differences can be identified in the price-movement patterns of the selected pharmaceutical and healthcare companies, and which groups of companies exhibit similar behaviour?

## Main Analysis

The notebook includes:

* Exploratory analysis and data preprocessing
* Descriptive statistics of QS Medicine ranking data
* Country-level analysis of university participation and performance
* Geospatial visualisations of QS Medicine rankings
* Pharmaceutical and healthcare stock-market analysis
* Stock returns and volatility analysis
* Country-level regression analysis
* Regression diagnostic visualisations
* Richter Gedeon case study
* Rolling volatility and price-trend analysis
* Dynamic Time Warping (DTW) similarity analysis
* Hierarchical clustering of company price movements
* Interactive visualisation components

The project uses both conventional and more specialised visualisation techniques, including **geospatial maps, time-series visualisation, regression diagnostics, DTW heatmaps and hierarchical clustering**.

## Data

The repository contains the datasets required for the analysis.

### University ranking data

QS World University Rankings by Subject – Medicine data are provided for:

* 2024
* 2025
* 2026

The data include university, country and ranking-score information used to examine changes in university participation and performance.

### Stock-market data

Stock-market data were collected for selected pharmaceutical and healthcare companies based on their headquarters country. A maximum of two companies was selected per country.

The stock data contain daily market information, including:

* Date
* Company
* Ticker
* Open
* High
* Low
* Close
* Adjusted Close
* Volume

Adjusted Close prices are used for the stock-return calculations.

The stock dataset covers approximately **2010–August 2026**.

## Repository Contents

The main files in this repository are:

* **Jupyter Notebook (`.ipynb`)** – complete analysis, visualisations and modelling
* **QS Medicine datasets** – ranking data for 2024–2026
* **Stock-market dataset** – selected pharmaceutical and healthcare companies

The notebook contains additional exploratory analysis and visualisations beyond those selected for the final coursework report.

## Notes on Reproducibility

The analysis was developed in **Jupyter Notebook using Python**. Random processes used in analytical methods are controlled where appropriate using fixed random states.

The notebook documents the main data preparation, analysis and visualisation steps so that the results can be reproduced from the provided datasets.

## Ethical and Data Considerations

The project uses publicly available aggregate university ranking and financial market data. No personal or sensitive information is used.

The analysis is intended for educational and exploratory purposes. Stock-market performance and university ranking outcomes are influenced by many factors, and the results should not be interpreted as establishing causal relationships.

## Coursework Context

This repository supports the accompanying coursework project report. The project report presents selected visualisations and findings from the broader analysis contained in the notebook.

The repository therefore includes some exploratory analyses and visualisations that are not included in the final report due to the report word-count limit.
