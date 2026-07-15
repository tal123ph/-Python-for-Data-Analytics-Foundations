# 🐍 Python for Data Analytics — Foundations

A hands-on collection of notebooks covering the core Python data-analytics stack: **NumPy**, **Pandas**, data cleaning & EDA, JSON handling, and web scraping. Built during the foundational stage of my Data Analytics / AI-ML learning path, focused on practical, project-based practice rather than pure theory.

## 📁 Project Structure

```
python-data-analytics-foundations/
│
├── NumPy/
│   └── numpy_1.ipynb                # Arrays, performance vs Python lists, indexing, functions
│
├── Pandas/
│   └── pandas.ipynb                 # Series, DataFrames, cleaning, grouping, merging, concatenation
│
├── Data Cleaning & EDA/
│   ├── Data_Cleaning_P1.ipynb       # Retail Sales EDA mini-project (feature engineering, CLV, AOV)
│   └── Assignment_Problem.ipynb     # Groupby exercises on Iris & Titanic datasets
│
├── JSON & Data Structuring/
│   └── thinking_data.ipynb          # Loading, cleaning, and structuring JSON data
│
├── Web Scraping/
│   ├── web scraping.ipynb           # REST API scraping (Harry Potter Books API)
│   ├── web_scrap_pro.ipynb          # BeautifulSoup scraping (quotes.toscrape.com), multi-page loop
│   └── web_scraping_projects/       # Saved raw HTML pages used for offline parsing
│
├── data/
│   ├── IRIS.csv
│   ├── SQL_Sale.csv
│   ├── Titanic-Dataset.csv
│   ├── global_air_quality_data_10000.csv
│   ├── raw_data.csv
│   ├── Sorted_data.csv
│   └── store_data.json
│
├── cleaned_data/
│   └── data.csv                     # Cleaned output from web scraping pipeline
│
├── cleaned_life_quotes_data/
│   └── data.csv                     # Cleaned quotes dataset (author, text)
│
└── README.md
```

## 🚀 What's Inside

### 🔢 NumPy
- Creating and inspecting arrays (1D, 2D, multi-dimensional)
- Array properties and data types
- Performance comparison: NumPy arrays vs. native Python lists (speed & memory)
- Key NumPy operations and functions

### 🐼 Pandas
- Creating `Series` and `DataFrame` objects
- Indexing, filtering with the `.query()` method
- Handling duplicates and cleaning data
- Feature engineering and column transformations (e.g., reordering columns)
- Group-by aggregation
- Merging, joining, and concatenating DataFrames

### 🧹 Data Cleaning & EDA
- **Retail Sales Analysis (mini end-to-end project)** — cleaning missing values, fixing data types, handling duplicates
- Feature engineering: `total_amount`, `High Value` / `Low Value` flags
- Customer Lifetime Value (CLV) and Average Order Value (AOV) calculations
- Purchase frequency segmentation (Frequent vs. Occasional buyers)
- Group-by exercises on the Iris and Titanic datasets

### 🗂️ JSON & Data Structuring
- Loading and parsing JSON data (`store_data.json`)
- Cleaning and structuring raw records
- Working toward extracting meaningful insights and a simple recommendation feature

### 🌐 Web Scraping
- **API scraping** — pulling structured data from a public REST API (Harry Potter Books API)
- **HTML scraping with BeautifulSoup** — multi-page scraping loop against `quotes.toscrape.com`, saving raw HTML locally and parsing it into a clean CSV (`author`, `text`)

## 🛠️ Tech Stack

- **Python 3**
- **NumPy** — array operations & performance
- **Pandas** — data manipulation and analysis
- **Requests / BeautifulSoup** — web scraping
- **JSON** — data parsing and structuring
- **Jupyter Notebook**

## ▶️ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/tal123ph/python-data-analytics-foundations.git
   cd python-data-analytics-foundations
   ```

2. Install the required libraries:
   ```bash
   pip install numpy pandas requests beautifulsoup4 jupyter
   ```

3. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

4. Open any notebook and run the cells. Notebooks that read a CSV/JSON file expect it in the same folder (see the `data/` folder above).

## 🎯 Purpose

This repository documents my foundational practice in Python for data analytics — building fluency in NumPy and Pandas, learning to clean and explore real-world datasets, and getting comfortable pulling data from APIs and web pages. It's a stepping stone toward the more advanced machine learning work in my other repositories, and part of my portfolio as an aspiring **AI Engineer / Data Scientist**.

## 👤 Author

**Muhammad Talha**
Data Analytics Student | Aspiring AI Engineer & Data Scientist
- GitHub: [@tal123ph](https://github.com/tal123ph)
- LinkedIn: [muhammad-talha12b](https://www.linkedin.com/in/muhammad-talha12b)

## 📄 License

This project is open source and available for learning purposes.
