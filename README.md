# Vegetable Market Analysis

## Project Overview


The **Vegetable Market Analysis** project, leveraging data from **Website:** https://vegetablemarketprice.com, delves deep into Noida's vibrant vegetable market along with neighboring markets in Delhi and Agra. It encompasses a multifaceted exploration of these dynamic sectors, including meticulous data collection, rigorous preprocessing, insightful trend analysis, and meticulous seasonal variation examination. Furthermore, it offers a keen understanding of the diverse preferences within income groups. To broaden the horizon, the project extends to a comprehensive case study on the quick-commerce vegetable business landscape in Delhi.

This project offers a comprehensive perspective on regional vegetable markets, incorporating data-driven insights and systematic analysis to uncover trends and patterns.

## Table of Contents
- [Aim/Objectives](#aimobjectives)
- [Problem Statement](#problem-statement)
- [Folder Structure](#folder-structure)
- [Tools, Libraries, and Techniques](#tools-libraries-and-techniques)
- [Overview of Data Exploration](#overview-of-data-exploration)
- [Primary Insights](#primary-insights)
- [Summary](#summary)
- [Learnings and Challenges](#learnings-and-challenges)


## Aim/Objectives

Our project aimed to:

1. **Analyze Price Trends**: Investigate and visualize price trends for various vegetables in the Noida market.

2. **Seasonal Variations**: Identify seasonal vegetables and analyze their price variations over time.

3. **Income Group Preferences**: Explore the preferences and buying behaviors of distinct income groups.

4. **Market Comparison**: Compare vegetable prices between Noida and nearby markets to uncover disparities.

5. **Quick-Commerce Study**: Conduct a comprehensive study on the potential and challenges of the quick-commerce vegetable business in Delhi.

## Problem Statement

Our project addressed the following key challenges:

- Analyzing and visualizing complex price trends for multiple vegetables.
- Identifying seasonal patterns and their impact on vegetable prices.
- Exploring the relationship between income groups and vegetable preferences.
- Comparing vegetable prices across different markets to understand regional variations.
- Assessing the potential and challenges of the quick-commerce vegetable business in a competitive market like Delhi.

## Folder Structure

Here's the project's folder structure:

| Folder/ File                                      | Description                                                                                                        |
|---------------------------------------------------|--------------------------------------------------------------------------------------------------------------------|
| **[Web Scraping & Preprocessing](Web%20Scraping%20&%20Preprocessing)**                  | Contains Python scripts and files for web scraping and preprocessing.                                           |
|   - [Scraped Data](Web%20Scraping%20&%20Preprocessing/Scraped%20Data)                                | Contains CSV files with scraped data.                                                                             |
|     - [`CSV_Delhi.csv`](Web%20Scraping%20&%20Preprocessing/Scraped%20Data/CSV_Delhi.csv)                            | CSV file for Delhi market data.                                                                                  |
|     - [`CSV_Noida.csv`](Web%20Scraping%20&%20Preprocessing/Scraped%20Data/CSV_Noida.csv)                            | CSV file for Noida market data.                                                                                  |
|     - [`CSV_Agra.csv`](Web%20Scraping%20&%20Preprocessing/Scraped%20Data/CSV_Agra.csv)                             | CSV file for Agra market data.                                                                                   |
|   - [helper](Web%20Scraping%20&%20Preprocessing/helper)                                        | Contains supporting files for data extraction.                                                                   |
|     - [`Dates.xlsx`](Web%20Scraping%20&%20Preprocessing/helper/Dates.xlsx)                               | Excel file with date-related information.                                                                        |
|   - [`Scraping with Preprocessing Code.ipynb`](Web%20Scraping%20&%20Preprocessing/Scraping%20with%20Preprocessing%20Code.ipynb)      | Jupyter Notebook file with combined code for web scraping and preprocessing.                                     |
|                                                   |                                                                                                                    |
| **[Analysis](Analysis)**                                      | Contains files related to data analysis and presentations.                                                       |
|   - [`case study.xlsx`](Analysis/case%20study.xlsx)                            | Excel file with details of the case study.                                                                       |
|   - [`final excel.xlsm`](Analysis/final%20excel.xlsm)                           | Excel file with analysis and visualizations.                                                                     |
|                                                   |                                                                                                                    |
| **[Project Presentation.pptx](Project%20Presentation.pptx)**                    | PowerPoint presentation for the project.                                                                         |


## Tools, Libraries, and Techniques

- **Data Extraction**: We utilized the Selenium library in Python for web scraping.
- **Data Preprocessing**: Data cleaning and preprocessing were primarily done using Microsoft Excel.
- **Data Analysis**: We used Python libraries such as Pandas and Matplotlib for data analysis and visualization.
- **Statistical Analysis**: Statistical tests were applied to identify significant trends.
- **Machine Learning**: We employed clustering algorithms for market segmentation.


## Overview of Data Exploration

Our data exploration phase involved:

- Data collection from reliable online sources.
- Cleaning and preprocessing data to handle missing values and inconsistencies.
- Calculation of average monthly prices for vegetables.
- Seasonal price index charts to visualize trends.
- Analysis of income group preferences using charts and statistics.
- Comparing vegetable prices across Noida, Delhi, and Agra markets.
- In-depth study of the quick-commerce vegetable business in Delhi.

## Visulization
<img src="https://github.com/AmarjeetRoy/Vegetable_Market_Analysis/assets/137817362/10cae715-8210-40dd-b9b3-779323dd6801" >
<br>
<img src="https://github.com/AmarjeetRoy/Vegetable_Market_Analysis/assets/137817362/608b2493-f2ed-4785-a6be-9eb4ffe33ab7" >

<br>


## Primary Insights

Our analysis yielded the following key insights:

### Price Trends

- Vegetable prices in Noida consistently remained lower than those in Delhi and Agra for most selected vegetables, making it an attractive market for consumers.

### Seasonal Variations

- Seasonal variations significantly influenced consumer buying patterns. For instance, during the winter season, there was a notable increase in the demand for leafy greens, leading to price spikes.

### Income Group Preferences

- Low-income groups experienced a 21% increase in their basket price compared to the previous period. In contrast, the middle-income group saw a 20% decrease, indicating improved affordability and a wider range of vegetable choices.

### Market Comparison

- Our analysis revealed that Noida's vegetable prices were consistently lower, suggesting potential cost savings for consumers compared to Delhi and Agra.

### Quick-Commerce Study

- Delhi's thriving economy, rising disposable income levels, and increasing internet penetration indicated a lucrative market for quick-commerce vegetable businesses. The urban lifestyle and busy demographic further underscored the demand for convenient online grocery shopping.


## Summary

In conclusion, the Vegetable Market Analysis project provided valuable insights into the dynamics of the Noida vegetable market. Our analysis of price trends, seasonal variations, income group preferences, and market comparisons highlighted key trends and opportunities. The study of the quick-commerce vegetable business in Delhi unveiled a promising market with specific challenges. Our findings serve as a valuable resource for stakeholders in the vegetable market.

## Learnings and Challenges

### Learnings

- Effective data extraction and preprocessing are essential for meaningful analysis.
- Seasonal variations have a significant impact on consumer behavior and prices.
- Understanding income group preferences is crucial for market targeting.
- Detailed market comparisons reveal regional variations and competitive advantages.

### Challenges

- Data extraction from online sources can be challenging and time-consuming.
- Analyzing and visualizing complex price

### Future Scope

In the future, this project can be expanded by incorporating additional data sources, conducting further analysis on specific vegetable types, and exploring additional markets. The insights gained from this project can be used to develop strategies for farmers, retailers, and consumers in the vegetable market.

