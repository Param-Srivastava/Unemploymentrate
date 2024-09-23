# Unemployment Rate Analysis Across Industries

## Introduction

This project focuses on analyzing unemployment rates across various industries over a span of years. Using a dataset that tracks unemployment rates for different industries like Agriculture, Business services, Manufacturing, Government, and more, the project performs a detailed statistical and time series analysis. It visualizes trends and patterns using various plotting techniques such as box plots, time series graphs, and correlation heatmaps.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)

## Dataset

The dataset includes unemployment rates across several industries from various dates. Key industries tracked include:

- Agriculture
- Business Services
- Construction
- Durable Goods Manufacturing
- Education and Health
- Finance
- Government
- Information
- Leisure and Hospitality
- Manufacturing
- Mining and Extraction
- Nondurable Goods Manufacturing
- Other
- Self-employed
- Transportation and Utilities
- Wholesale and Retail Trade

### Time Period

The data spans multiple years, with entries on dates such as `2001-02-01`, `2003-04-01`, etc.

### Industries

The unemployment rates are provided for the following sectors:

- Agriculture
- Business Services
- Construction
- Durable Goods Manufacturing
- Education and Health
- Finance
- Government
- Information
- Leisure and Hospitality
- Manufacturing
- Mining and Extraction
- Nondurable Goods Manufacturing
- Other
- Self-employed
- Transportation and Utilities
- Wholesale and Retail Trade

## Features

The project performs various types of analysis and visualizations:

- **Box Plot Distribution**: Visualizes the spread and outliers in unemployment rates across industries.
- **Trend Analysis**: Tracks the changes in unemployment rates over the years for different industries.
- **Time Series Analysis**: Applies multiple time series techniques to identify trends and cyclic behavior in unemployment rates.
- **Correlation Heatmap**: Plots correlations between unemployment rates of different industries to find relationships.

## Installation

To set up the project environment and run the analysis, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/Unemploymentrate.git
   cd unemployment-analysis
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

To run the analysis, use the following steps:

1. Load the dataset and ensure it's in the proper format (CSV or another structured format).
2. Execute the main analysis script:

   ```bash
   python analyze.py
   ```

3. The results, including plots and statistical summaries, will be saved in the `output/` directory.
