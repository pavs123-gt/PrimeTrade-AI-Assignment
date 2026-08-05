# PrimeTrade-AI-Assignment

## Objective
This project analyzes the relationship between cryptocurrency market sentiment and trader performance using historical trading data and the Fear & Greed Index.

The analysis includes data preprocessing, exploratory data analysis (EDA), statistical analysis, and data visualizations to understand how different market sentiments influence trading outcomes, profitability, trade size, execution price, and trading activity.

The project is implemented using Python in Google Colab with Pandas, NumPy, Matplotlib, and Seaborn.

## 📑 Table of Contents

- [ Features](#features)
- [ Project Structure](#project-structure)
- [ Dataset](#dataset)
- [ Setup & Installation](#️setup--installation)
- [ Usage](#️usage)
- [ Exploratory Data Analysis](#exploratory-data-analysis)
- [ Visualizations](#visualizations)
- [ Key Findings](#key-findings)
- [ Technologies Used](#️technologies-used)
- [ Requirements](#requirements)
- [ Future Improvements](#future-improvements)
- [ License](#license)

 ##  Features
- Data cleaning and preprocessing
- Merging historical trading data with Fear & Greed Index
- Market sentiment classification
- Exploratory Data Analysis (EDA)
- Statistical analysis of trader performance
- Profit vs Loss analysis
- Distribution analysis of Closed PnL and Trading Fee
- Correlation Heatmap
- Visualization of trading metrics
- Summary of market sentiment insights
## Project Structure

```text
PrimeTrade-AI-Assignment/
│
├── PrimeTrade_AI_Assignment.ipynb    # Main analysis notebook
├── README.md                         # Project documentation
├── requirements.txt                  # Required Python libraries
├── fear_greed_index.csv              # Fear & Greed Index dataset
└── historical_data.csv               # Trading dataset (not included due to GitHub size limit)
```
## Dataset

The project uses two datasets:

### 1. fear_greed_index.csv

Contains historical Fear & Greed Index values.

**Download:**


---

### 2. historical_data.csv

Contains historical cryptocurrency trading data.

**Download:**
https://drive.google.com/file/d/PASTE_HISTORICAL_DATA_LINK_HERE/view?usp=sharing

## Setup & Installation
Clone the repository

git clone https://github.com/yourusername/PrimeTrade-AI-Assignment.git

Install dependencies

pip install -r requirements.txt

Open the notebook using Jupyter Notebook or Google Colab.
## Usage

1. Open the notebook.
2. Upload the datasets.
3. Execute all notebook cells.
4. View the statistical analysis.
5. Explore the visualizations.
## Exploratory Data Analysis

The notebook performs:

- Data Cleaning
- Missing Value Analysis
- Duplicate Removal
- Data Type Conversion
- Dataset Merging
- Statistical Summary
- Market Sentiment Analysis
  ## Visualizations

The project includes:

- Average Closed PnL by Market Sentiment
- Total Closed PnL by Market Sentiment
- Number of Trades by Market Sentiment
- Average Trade Size
- Average Execution Price
- Profit vs Loss Comparison
- Closed PnL Distribution
- Trading Fee Distribution
- Correlation Heatmap
  ## Key Findings

- Fear sentiment recorded the highest overall trading activity.
- Extreme Greed showed the highest average Closed PnL.
- Loss-making trades outnumbered profitable trades across all market sentiments.
- Trading fees were generally low, with a small number of high-fee outliers.
- Most Closed PnL values were concentrated around zero, while a few trades generated significantly larger profits or losses.
- Correlation analysis showed only weak relationships among most numerical variables.
  ## Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
  ## Requirements

Python 3.9+

Required Libraries

- pandas
- numpy
- matplotlib
- seaborn
  ## Future Improvements

- Build predictive machine learning models for trader performance.
- Perform time-series forecasting of market sentiment.
- Develop an interactive dashboard using Streamlit or Power BI.
- Incorporate additional technical indicators and market data.
  ## License

This project is developed for educational and assignment purposes.
