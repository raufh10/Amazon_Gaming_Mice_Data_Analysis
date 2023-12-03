# Amazon Bestseller PC Gaming Mice Analysis

## Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Repository Structure](#repository-structure)
- [Disclaimer](#disclaimer)
- [Data Analysis](analysis/analysis.ipynb)

## Project Overview

This project focuses on scraping Amazon's Bestseller list for PC gaming mice and conducting a thorough analysis of the collected data. The primary goal is to understand the market trends, pricing patterns, and features of the top-rated gaming mice. This analysis could serve businesses and individuals who are looking to understand the market and make informed decisions about their purchases.

## Features

- **Web Scraping**: A Python script that utilizes Beautiful Soup and playwright to extract data from Amazon's Bestseller page for gaming mice.
- **Data Cleaning**: Processing the raw data to prepare it for analysis, including handling missing values and normalizing data formats.
- **Data Analysis**: Using Python, particularly pandas , to analyze the data, supplemented by Jupyter Notebook for documentation and step-by-step explanation.
- **Visualization**: Generating visualizations using Matplotlib and Seaborn to represent the data graphically.

## Repository Structure

- `etl/` - Contains the web scraping script to collect data from Amazon. Also contains scripts to process the raw data.
- `analysis/` - Jupyter Notebooks with the exploratory data analysis and visualizations.
- `output/` - Contains processed data collected from Amazon.
- `README.md` - The guide and documentation for this repository.

## Disclaimer

The web scraping script provided in this repository is intended for educational purposes only. The author is not responsible for how this script is used, nor for any code lost or damages caused by this script.
