Insights into Factors Driving Changes in QS World University Rankings Total Scores

## Overview

This repository contains the data and Jupyter notebook used for the analysis of factors influencing QS World University Rankings (QS WUR) total scores.
Focusing on how individual QS ranking indicators contribute to overall ranking performance and how their relative importance changes across ranking years (2024–2026).

## Research Objectives

The analysis aims to:

- estimate missing QS WUR total scores using ranking indicators
- explore relationships between QS ranking indicators
- identify the contribution of individual indicators to overall scores
- examine changes in indicator importance across ranking years

## Repository Contents

- "QS_WUR_analysis.ipynb"
  Jupyter notebook containing the complete data processing, analysis, visualisations, and results.

- "QS_WUR_2024.xlsx"
  QS World University Rankings 2024 dataset used in the analysis.

- "QS_WUR_2025.xlsx"
  QS World University Rankings 2025 dataset used in the analysis.

- "QS_WUR_2026.xlsx"
  QS World University Rankings 2026 dataset used in the analysis.

## Methods

The analysis was conducted using Python and includes:

- data cleaning and preprocessing using Pandas
- linear regression for estimating missing total scores
- exploratory data analysis and visualisation
- correlation analysis
- network analysis of indicator relationships
- Shapley decomposition to evaluate indicator importance

## Tools and Libraries

The project uses:

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- NetworkX

## Data Source

The datasets are based on the QS World University Rankings datasets for 2024, 2025, and 2026, obtained from the official QS website.

## Reproducibility

The notebook contains the complete workflow from data preparation to final analysis. The included datasets allow the analysis to be reproduced.
