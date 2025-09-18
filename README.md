# My Data Science Journey

Welcome! 👋  
This repository is a collection of my **data science projects**.  
It serves as a portfolio showcasing the skills I've gained through hands-on practice — covering everything from **data cleaning and exploration** to **machine learning model development**.

---

## 📂 About This Repository

This repository is structured to reflect my learning path.  
Each folder represents a different project, often focusing on a particular **data science concept** or a **real-world problem**.

### 🔑 Project Categories

- **Exploratory Data Analysis (EDA):**  
  Projects focused on understanding and visualizing datasets to uncover key insights.

- **Machine Learning (ML) Models:**  
  Applications of various supervised and unsupervised learning algorithms to solve prediction and classification problems.

- **Data Cleaning and Preprocessing:**  
  Demonstrations of the crucial first steps in any data project, including handling missing values, feature engineering, and data normalization.

---

## First Project: analyzing_stock_data_yfinance.ipynb

### 📈 Extracting Stock Data Using Python

This project demonstrates how to **extract, analyze, and visualize stock data** using the `yfinance` library in Python.  
The lab focuses on **Apple (AAPL)** and **AMD (Advanced Micro Devices)** stock data, covering key financial concepts and hands-on data extraction techniques.

### 📝 About

A company's stock share is a piece of ownership in that company.  
- **Stock (Equity):** A security that represents ownership of a fraction of a corporation.  
- **Shares:** Units of stock.  
- **Trading:** Investors buy and sell shares daily, and prices fluctuate based on market dynamics.  
- **Ticker:** A continuously updated report of a stock's price provided by market exchanges.

As a **data scientist at a hedge fund**, your job is to detect suspicious activity in stock trading. This lab shows how to extract, clean, and explore stock data with Python

### 🔧 Tools & Libraries

- [yfinance](https://pypi.org/project/yfinance/) → To fetch stock market data.  
- [pandas](https://pandas.pydata.org/) → For data manipulation and analysis.  
- [matplotlib](https://matplotlib.org/) → For plotting stock trends.  
- [json](https://docs.python.org/3/library/json.html) → For working with JSON datasets.  

### 📂 Data Sources

- **Live Data:** Retrieved directly from Yahoo Finance via the `yfinance` API.  
- **Static Data:** Provided JSON files (`apple.json`, `amd.json`) for offline practice.

---

## Second Project: extracting_stock_data_webscraping.ipynb

### 🌐 Extracting Stock Data Using Web Scraping

Not all stock data is available via APIs like `yfinance`.  
In this project, we use **web scraping techniques** with **BeautifulSoup** and **pandas** to extract stock data directly from HTML tables.

### 📝 About

The focus is on **Netflix (NFLX)** and **Amazon (AMZN)** historical stock data.  
The workflow follows these steps:

1. **Send HTTP Request** → Fetch web page HTML with `requests`.  
2. **Parse HTML** → Use `BeautifulSoup` to structure the data.  
3. **Identify Table Elements** → Locate `<table>`, `<tr>`, `<td>` tags.  
4. **Extract Data** → Loop through rows and collect stock data.  
5. **Convert to DataFrame** → Store results in `pandas.DataFrame`.  

We also explore an alternative approach using **`pandas.read_html()`** for extracting tables directly.  

### 🔧 Tools & Libraries

- [requests](https://pypi.org/project/requests/) → To fetch web pages.  
- [BeautifulSoup (bs4)](https://pypi.org/project/beautifulsoup4/) → For parsing HTML.  
- [pandas](https://pandas.pydata.org/) → For tabular data handling.  
- [plotly](https://plotly.com/python/) → For interactive visualization.  

### 📂 Data Sources

- **Netflix Data:** Static HTML file ([netflix_data_webpage.html](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-PY0220EN-SkillsNetwork/labs/project/netflix_data_webpage.html))  
- **Amazon Data (Exercise):** Static HTML file ([amazon_data_webpage.html](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-PY0220EN-SkillsNetwork/labs/project/amazon_data_webpage.html))  

