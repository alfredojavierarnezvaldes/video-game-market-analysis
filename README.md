# video-game-market-analysis

Video Game Market Structural Analysis

# Project Overview

This project analyzes historical global video game sales data to identify long-term sales trends, platform performance differences, genre patterns, regional sales patterns, and changes in the concentration of recorded sales among individual game titles.

The objective is to describe sales evolution and examine changes in title-level sales concentration over time.


# Dataset

Source: Kaggle – Video Game Sales Dataset

Scope: Global video game sales recorded in the dataset

Variables analyzed: Year, Platform, Genre, Publisher, Global Sales

Note: The dataset does not provide information on sales channels such as physical or digital distribution.


# Methodology

The analysis includes:

- Data cleaning and preprocessing
- Aggregation of total sales by year, genre, and platform
- Comparative platform performance (total vs. average sales)
- Identification of high-performing titles
- Regional sales and genre analysis
- Correlation analysis between regional sales
- Regression analysis of post-peak recorded sales
- Pre-peak vs. post-peak comparison
- Analysis of title-level sales concentration using the Herfindahl–Hirschman Index (HHI)
- Visualization of sales and title-level concentration trends over time


# Key Findings

- The industry reached its highest recorded sales levels in the late 2000s.
- Total recorded sales show a general downward trend after the late-2000s peak, although the decline is not uniform across all years.
- Platform performance varies depending on whether total sales or average sales per title is considered.
- A small number of flagship titles achieve substantially higher recorded sales than most other titles.
- Sales performance varies substantially across genres, with Action, Sports, and Shooter recording the highest cumulative sales.
- Regional sales patterns and genre composition vary across markets.
- The average HHI indicates substantially higher concentration of recorded sales among individual game titles from 2015 onward.
- The post-peak regression identifies a strong negative linear trend in the recorded annual sales represented in the dataset; this result should not be interpreted as evidence of the causes of the decline or of a structural change in the overall industry.


# Structural Insight

- Post-2015 data indicates a higher concentration of recorded sales among individual game titles. However, this result does not by itself establish structural consolidation within the overall industry. The HHI analysis is applied to individual titles rather than firms, and the number of observed titles varies across years.

The analysis therefore describes changes in the distribution of recorded sales rather than providing definitive evidence about the underlying structure or causes of industry-wide changes.


# Limitations

- The dataset does not provide information on sales channels such as digital distribution or microtransactions.
- Analysis focuses on recorded sales rather than profitability.
- Results are limited to the variables and time period represented in the dataset.
- Comparisons of HHI across years should be interpreted cautiously because the number of observed titles varies considerably.
- The dataset does not contain information about mobile gaming or other market segments outside the variables represented in the source data.


# Future Improvements (Version 2.0)

- Incorporate digital sales data.
- Publisher-level concentration analysis.
- Regional market structure comparison.
- Structural break testing and regression modeling.
- Trend decomposition and predictive modeling.
- Integration of additional market segments, including mobile gaming.


# Technologies Used

- Python
- Pandas
- Matplotlib
- Scypy
- Jupyter Notebook
