# 📈 Trader Behavior Analysis Using Market Sentiment (Fear & Greed Index)

## 📌 Project Overview

This project explores the relationship between cryptocurrency trader behavior and overall market sentiment using historical trading data and the Fear & Greed Index. The objective is to understand how traders perform under different market conditions such as **Extreme Fear**, **Fear**, **Neutral**, **Greed**, and **Extreme Greed**.

The project follows a complete data analytics workflow, including data cleaning, preprocessing, exploratory data analysis (EDA), feature engineering, machine learning, and dashboard creation. An interactive dashboard is also developed to present key insights in a user-friendly format.

---

# 🎯 Business Problem

The cryptocurrency market is highly volatile and largely influenced by investor psychology. Market sentiment often drives trading decisions, but understanding how sentiment affects trader performance can be challenging.

This project aims to analyze historical trading records alongside the Fear & Greed Index to identify behavioral patterns, evaluate trading performance under different market conditions, and provide data-driven insights that can support better trading strategies and decision-making.

---

# 🎯 Project Objectives

The main objectives of this project are:

- Analyze historical cryptocurrency trading data.
- Integrate market sentiment data using the Fear & Greed Index.
- Clean and preprocess the datasets.
- Perform Exploratory Data Analysis (EDA) to identify trends and patterns.
- Engineer meaningful features for better analysis.
- Compare trader behavior across different market sentiment categories.
- Build a Machine Learning model for predictive analysis.
- Develop an interactive dashboard to visualize important KPIs and insights.

---

# 📂 Dataset Information

## Historical Trading Dataset

- **File:** `historical_data(2).csv`
- **Rows:** 211,224
- **Columns:** 16

The dataset contains historical cryptocurrency trading information, including:

- Account Details
- Cryptocurrency Coin
- Trade Side (Buy/Sell)
- Execution Price
- Trade Size (Token)
- Trade Size (USD)
- Closed Profit & Loss (PnL)
- Fees
- Timestamp
- Position Information
- Other transaction-related details

---

## Fear & Greed Index Dataset

- **File:** `fear_greed_index(2).csv`
- **Rows:** 2,644
- **Columns:** 4

This dataset provides daily market sentiment information, including:

- Date
- Timestamp
- Fear & Greed Value
- Sentiment Classification

The sentiment values are later combined with the trading dataset to study how market psychology influences trading outcomes.

---

# 🛠️ Technologies Used

This project utilizes the following tools and technologies:

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook
- HTML Dashboard
- Git
- GitHub

---

# 🔄 Project Workflow

```text
Historical Trading Data
                +
Fear & Greed Index
                │
                ▼
        Data Collection
                │
                ▼
     Data Cleaning & Preprocessing
                │
                ▼
       Feature Engineering
                │
                ▼
  Exploratory Data Analysis (EDA)
                │
                ▼
      Business Insight Generation
                │
                ▼
 Machine Learning Model Development
                │
                ▼
 Interactive Dashboard & Reporting
```

---

# 🧹 Data Cleaning & Preprocessing

The analysis notebook performs several preprocessing steps before analysis:

- Loaded both datasets into Python.
- Inspected dataset dimensions and structure.
- Verified data types of all columns.
- Checked for missing values.
- Checked for duplicate records.
- Converted timestamp columns into appropriate datetime format.
- Prepared both datasets for merging.
- Merged historical trading data with the Fear & Greed Index using date information.
- Created a cleaned dataset for exploratory analysis and machine learning.

---

# 📊 Exploratory Data Analysis (EDA)

The project performs exploratory analysis to better understand trader behavior and market sentiment.

## Univariate Analysis

- Distribution of trading records.
- Distribution of Fear & Greed categories.
- Individual feature analysis.

## Bivariate Analysis

- Comparison of trader performance across sentiment categories.
- Relationship between trade size and profit/loss.
- Buy vs Sell trading behavior.

## Trend Analysis

- Trading activity over time.
- Market sentiment changes over time.
- Profitability trends across different periods.

## Trader Performance Analysis

- Identification of top-performing traders.
- Identification of lower-performing traders.
- Comparison of trader performance under different market conditions.

---

# ⚙️ Feature Engineering

After cleaning the data, additional features were created to improve analysis and support machine learning.

These engineered features were used for:

- Better trader segmentation.
- Enhanced business analysis.
- Improved predictive modeling.

---

# 🤖 Machine Learning

A separate notebook is included for the Machine Learning implementation.

The workflow consists of:

- Data preprocessing.
- Feature preparation.
- Train-Test Split.
- Decision Tree Classification model.
- Model training.
- Model prediction.
- Model evaluation.

The notebook uses Scikit-learn libraries such as:

- `train_test_split`
- `DecisionTreeClassifier`
- `accuracy_score`
- `classification_report`

---

# 📈 Interactive Dashboard

An interactive HTML dashboard is included with the project.

The dashboard provides visual insights into:

- Overall trading performance.
- Market sentiment distribution.
- Trader profitability.
- Trading activity.
- Important KPIs.
- Business insights.

The dashboard enables users to interactively explore the results and better understand the relationship between market sentiment and trader performance.

---

# 💡 Key Insights

The analysis focuses on understanding:

- How market sentiment influences trader behavior.
- Whether traders perform better during Fear or Greed market conditions.
- How profitability changes under different sentiment categories.
- Trading activity patterns over time.
- Overall trader performance based on historical records.

---

# 📁 Project Structure

```text
Trader-Sentiment-Analysis/
│
├── A Trader_Sentiment_Analysis.ipynb
├── model.ipynb
├── historical_data(2).csv
├── fear_greed_index(2).csv
├── crypto_sentiment_dashboard (1).html
└── README.md
```

---

# ▶️ How to Run

1. Clone the repository.

```bash
git clone https://github.com/yourusername/Trader-Sentiment-Analysis.git
```

2. Navigate to the project folder.

```bash
cd Trader-Sentiment-Analysis
```

3. Install the required Python libraries.

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

4. Launch Jupyter Notebook.

```bash
jupyter notebook
```

5. Run the notebooks in the following order:

- `A Trader_Sentiment_Analysis.ipynb`
- `model.ipynb`

6. Open `crypto_sentiment_dashboard (1).html` in your browser to view the interactive dashboard.

---

# 📦 Requirements

```text
pandas
numpy
matplotlib
seaborn
scikit-learn
jupyter
```

---

# 📄 Project Files

| File | Description |
|------|-------------|
| `A Trader_Sentiment_Analysis.ipynb` | Performs data cleaning, preprocessing, exploratory data analysis (EDA), feature engineering, data visualization, and business analysis. |
| `model.ipynb` | Contains the machine learning workflow including preprocessing, model training, prediction, and evaluation. |
| `historical_data(2).csv` | Historical cryptocurrency trading records used for analysis. |
| `fear_greed_index(2).csv` | Daily Fear & Greed Index data representing market sentiment. |
| `crypto_sentiment_dashboard (1).html` | Interactive dashboard for visualizing project findings and insights. |

---

# ✅ Conclusion

This project demonstrates a complete end-to-end data analytics workflow by combining cryptocurrency trading history with market sentiment data. The analysis includes data preprocessing, exploratory data analysis, feature engineering, predictive modeling, and interactive visualization. The findings help illustrate how trader behavior varies across different market sentiment conditions.

---

# 👨‍💻 Author

**Name:** Ankit kumar

**GitHub:** https://github.com/Ankitkumar1511
