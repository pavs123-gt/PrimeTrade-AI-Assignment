# PrimeTrade-AI-Assignment

## Objective
This project analyzes the relationship between cryptocurrency market sentiment and trader performance using historical trading data and the Fear & Greed Index.

The analysis includes data preprocessing, exploratory data analysis (EDA), statistical analysis, and data visualizations to understand how different market sentiments influence trading outcomes, profitability, trade size, execution price, and trading activity.

The project is implemented using Python in Google Colab with Pandas, NumPy, Matplotlib, and Seaborn.

## 📑 Table of Contents

- [ Features](#features)
- [ Project Structure](#project-structure)
- [ Dataset](#dataset)
- [Setup and Installation](#setup-and-installation)
- [Usage](#usage)
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
https://drive.google.com/file/d/1qlPps0aySSCfV0JOGqq2HhZRHCBQsnDS/view?usp=sharing

---

### 2. historical_data.csv

Contains historical cryptocurrency trading data.

**Download:**
https://drive.google.com/file/d/1vHfiuPGjVYIGKhAhQX9DQwNEYsrjoWvc/view?usp=sharing

## Setup and Installation

### 1. Clone the Repository

```bash
git clone https://github.com/pavs123-gt/PrimeTrade-AI-Assignment.git
```

### 2. Navigate to the Project Folder

```bash
cd PrimeTrade-AI-Assignment
```

### 3. Install Required Libraries

```bash
pip install -r requirements.txt
```

### 4. Download the Datasets

Download both datasets from the links provided in the **Dataset** section and place them inside the project folder.

### 5. Launch the Notebook

Open the notebook using **Google Colab** or **Jupyter Notebook**.

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

The project generates the following visualizations to analyze the relationship between market sentiment and trader performance.

### 1. 

![Average Closed PnL](https://github.com/pavs123-gt/PrimeTrade-AI-Assignment/blob/main/Aversge%20Closed%20Pnl.png)

---

### 2. 

![Total Closed PnL](https://github.com/pavs123-gt/PrimeTrade-AI-Assignment/blob/main/Total%20Closed%20Pnl.png)

---

### 3. 

![Number of Trades](https://github.com/pavs123-gt/PrimeTrade-AI-Assignment/blob/main/No.of_Trades.png)

---

### 4.

![Average Trade Size](https://github.com/pavs123-gt/PrimeTrade-AI-Assignment/blob/main/Average_Trade_Size.png)

---

### 5. 

![Average Execution Price](https://github.com/pavs123-gt/PrimeTrade-AI-Assignment/blob/main/Average_Execution_Price.png)

---

### 6. 

![Profit vs Loss](https://github.com/pavs123-gt/PrimeTrade-AI-Assignment/blob/main/Profit_vs_Loss.png)

---

### 7. 

![Closed PnL Distribution](https://github.com/pavs123-gt/PrimeTrade-AI-Assignment/blob/main/Distrubution_of_closed_pnl.png)

---

### 8. 

![Trading Fee Distribution](https://github.com/pavs123-gt/PrimeTrade-AI-Assignment/blob/main/Distribution_of_TradingFree.png)

---

### 9.

![Correlation Heatmap](https://github.com/pavs123-gt/PrimeTrade-AI-Assignment/blob/main/Heatmap.png)
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
This project is shared for educational and evaluation purposes only. All rights are reserved by the author.
