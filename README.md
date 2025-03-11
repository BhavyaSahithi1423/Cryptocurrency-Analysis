# Cryptocurrency Analysis

## Project Overview
This project involves analyzing cryptocurrency data through three main stages:
1. **Web Scraping:** Used the public open API of [Coindesk](https://www.coindesk.com/) to scrape real-time cryptocurrency data.
2. **Exploratory Data Analysis (EDA):** Analyzed historical data from Kaggle, which consists of 23 CSV files, each representing a different cryptocurrency.
3. **Dashboard & Insights:** Developed an interactive dashboard incorporating data transformations, DAX calculations, and key insights.

---

## Features & Insights
### **1. Web Scraping**
- Collected real-time data for 19 cryptocurrencies using Coindesk API.
- Extracted values like Open, High, Low, and Close prices.
- Stored the scraped data in a CSV file.

### **2. Exploratory Data Analysis (EDA)**
- Merged all 23 cryptocurrency files from the Kaggle dataset into a single dataframe.
- Conducted statistical analysis and visualizations.
- Key visualizations include:
  - Market capitalization of top cryptocurrencies.
  - Price trends and volatility analysis.
  - Correlation between cryptocurrencies.

### **3. Dashboard Insights**
The dashboard provides answers to the following:
1. **Final Close Price**
2. **Highest Close Price**
3. **Lowest Close Price**
4. **Average Daily Volume**
5. **Comparison of Close Prices over a selected period**
6. **Average Volume over a Date Range**
7. **Price Comparison Table for various cryptocurrencies**
8. **Top Performers in the last 30 and 365 Days**
9. **Worst Performers in the last 30 and 365 Days**
10. **Correlation of Prices among Cryptocurrencies**

---

## Technologies Used
- **Python:** Data scraping and EDA
- **Libraries:** Requests, Pandas, NumPy, Matplotlib, Seaborn, Plotly
- **Power BI:** Dashboard and Data Visualization
- **DAX:** Data transformations and calculated insights

---

## Installation & Setup
### **1. Web Scraping Setup**
- Install required libraries:
  ```bash
  pip install requests pandas numpy
  ```
- Run the `web_scraping.py` script to fetch the latest data.

### **2. EDA Setup**
- Install required libraries:
  ```bash
  pip install pandas matplotlib seaborn plotly
  ```
- Run the `eda.py` script to generate insights and visualizations.

### **3. Dashboard Setup**
- Load the cleaned dataset into Power BI.
- Apply necessary transformations and build visualizations.

---

## Conclusion
This project provides a comprehensive analysis of cryptocurrency data, from real-time data collection to in-depth EDA and insightful visualizations through a dashboard. The insights derived can help investors and analysts understand market trends and make data-driven decisions.

