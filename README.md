# 📈 Task 7: Time Series Analysis on Apple Stock Prices

## Synent Technologies Data Science Internship

### 📌 Project Overview

This project focuses on analyzing historical Apple Inc. (AAPL) stock price data using Time Series Analysis techniques. The objective is to identify trends and patterns in stock market behavior over time through data visualization and moving average analysis.

This project was completed as part of **Task 7 – Time Series Analysis** in the Synent Technologies Data Science Internship Program.

---

## 🎯 Problem Statement

Stock prices fluctuate daily and generate large amounts of time-dependent data. Understanding historical trends helps investors and analysts make informed decisions.

The goal of this project is to:

* Analyze Apple stock price movements over time
* Detect overall market trends
* Visualize changes in stock prices
* Apply moving averages to smooth short-term fluctuations

---

## 📊 Dataset Details

**Dataset Name:** AAPL.csv

**Description:**
The dataset contains historical stock market data for Apple Inc. (AAPL), including daily trading information.

### Features Used

| Feature   | Description                    |
| --------- | ------------------------------ |
| Date      | Trading date                   |
| Open      | Opening stock price            |
| High      | Highest stock price of the day |
| Low       | Lowest stock price of the day  |
| Close     | Closing stock price            |
| Adj Close | Adjusted closing price         |
| Volume    | Number of shares traded        |

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Google Colab

---

## 📈 Methodology

### 1. Data Loading

* Imported the AAPL.csv dataset using Pandas.
* Loaded stock price records into a DataFrame.

### 2. Data Preprocessing

* Converted the Date column into datetime format.
* Verified dataset structure and data types.
* Prepared data for time-based analysis.

### 3. Trend Analysis

* Visualized stock closing prices over time.
* Identified long-term growth and fluctuation patterns.

### 4. Moving Average Analysis

* Calculated the 30-Day Moving Average (MA30).
* Compared daily closing prices with the moving average trend.

### 5. Data Visualization

Created visual representations of:

* Apple Stock Closing Price Trend
* Closing Price vs 30-Day Moving Average

---

## 📷 Visualizations

### Stock Price Trend

![Stock Price Trend](images/stock_price_trend.png)

### 30-Day Moving Average Analysis

![Moving Average Analysis](images/moving_average_analysis.png)

---

## 🔍 Key Insights

* Apple stock prices show significant variation over time.
* Long-term market trends become more visible through moving averages.
* The 30-Day Moving Average helps reduce daily market noise.
* Time series analysis provides a clearer understanding of stock performance patterns.

---

## ✅ Results

Successfully analyzed historical Apple stock price data using Time Series Analysis techniques.

Achievements:

* Performed trend analysis on stock prices.
* Calculated and visualized a 30-Day Moving Average.
* Identified long-term movement patterns in Apple stock performance.
* Generated meaningful visual insights from time-series data.

---

## 📂 Repository Structure

```text
synent-task7-timeseriesanalysis-sanjanamonteiro
│
├── Task_7_Time_Series.ipynb
├──  AAPL.csv
├── images/
│   ├── stock_price_trend.png
│   └── moving_average_analysis.png
└── README.md
```

---

## ▶️ How to Run

1. Clone the repository.
2. Open the notebook in Google Colab or Jupyter Notebook.
3. Install required libraries:

pip install pandas numpy matplotlib

4. Ensure AAPL.csv is available in the data folder.
5. Run all notebook cells sequentially.

---

## 🎓 Internship Information

**Organization:** Synent Technologies
**Domain:** Data Science Internship
**Task:** Task 7 – Time Series Analysis

---

## 👩‍💻 Author

**Sanjana Monteiro**

Data Science Intern
