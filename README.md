# Superstore Sales Analysis

An end-to-end retail sales analytics project using **Python and Microsoft Power BI** to explore sales performance, customer behaviour, product performance, regional trends, shipping patterns, and key business KPIs.

The project demonstrates a complete analytics workflow — from data cleaning and exploratory analysis in Python to interactive business intelligence reporting in Power BI.

## 📌 Project Overview

Retail organisations generate large volumes of transactional data, but raw data alone does not provide actionable business insight.

This project analyses a Superstore-style retail dataset to answer important business questions such as:

- How are sales performing over time?
- Which regions and categories generate the most sales?
- Which customer segments contribute most to revenue?
- Which products and sub-categories perform best?
- How does sales performance change throughout the year?
- Which shipping methods are most frequently used?
- What KPIs can be used to monitor overall sales performance?

The analysis was performed using **Python for data preparation and exploratory analysis**, followed by **Power BI for interactive dashboard development and business reporting**.

## 🎯 Project Objectives

The main objectives of this project are to:

- Clean and prepare raw retail transaction data
- Perform exploratory data analysis
- Analyse sales trends over time
- Compare regional and category performance
- Analyse customer segments
- Identify high-performing products and sub-categories
- Examine shipping patterns
- Calculate key business performance indicators
- Build an interactive Power BI dashboard
- Translate analytical findings into meaningful business insights

## 🛠️ Tools & Technologies

### Programming & Data Analysis
- **Python**
- **Pandas**
- **Matplotlib**
- **Seaborn**
- **Jupyter Notebook**

### Business Intelligence
- **Microsoft Power BI**
- **Power Query**
- **DAX**

### Version Control
- **Git**
- **GitHub**

## 🔄 Project Workflow

```text
Raw Dataset
     ↓
Data Cleaning & Preparation
     ↓
Exploratory Data Analysis
     ↓
Feature Engineering
     ↓
KPI Analysis
     ↓
Business Insights
     ↓
Power BI Data Model
     ↓
Interactive Dashboard
```

## 📊 Data Preparation

The dataset was prepared before performing the analysis.

Key data preparation activities included:

- Inspecting the dataset structure
- Identifying missing values
- Checking data types
- Converting fields into appropriate formats
- Preparing date-related fields
- Reviewing duplicate or inconsistent records
- Creating analytical features required for KPI calculations
- Preparing the cleaned dataset for visualisation and reporting

## 🔎 Exploratory Data Analysis

The exploratory analysis focused on understanding the main drivers of sales performance.

### Sales Analysis
- Overall sales performance
- Monthly sales trends
- Sales by region
- Sales by category
- Sales by sub-category
- Sales by customer segment

### Product Analysis
- Top-performing products
- Product and sub-category performance
- Contribution of different categories to overall sales

### Customer Analysis
- Customer contribution to sales
- Customer segments
- Order and customer-level performance

### Shipping Analysis
- Shipping mode distribution
- Relationship between shipping patterns and orders

## 📈 Key Performance Indicators

The project includes analysis of important sales KPIs, including:

- **Total Sales**
- **Total Orders**
- **Unique Customers**
- **Average Order Value (AOV)**
- **Sales Growth**

These KPIs provide a high-level view of business performance while allowing users to investigate the underlying trends through the dashboard.

## 📊 Power BI Dashboard

The Power BI dashboard converts the analytical results into an interactive business intelligence report.

### Dashboard Visualisations

The dashboard includes:

- Sales by Category
- Sales by Segment
- Sales by Region
- Sales by Sub-Category
- Top 10 Products by Sales
- Monthly Sales Trend
- KPI Cards
- Year filters
- Region filters
- Interactive filtering

The dashboard allows users to explore sales performance from different business perspectives rather than relying only on static charts.

## 💡 Key Insights

The analysis identified several notable patterns within the dataset:

- The **West region** recorded the strongest sales performance among the regions analysed.
- **Technology** was the strongest-performing category in terms of sales.
- Sales showed stronger performance toward the **end of the year**, indicating seasonal variation.
- **Standard shipping** represented a significant proportion of shipping activity.
- Product and sub-category analysis highlighted differences in sales contribution across the portfolio.

> **Data limitation:** This dataset does not contain a Profit field, so the project does **not** make profit or profitability claims.

## 📁 Repository Structure

```text
superstore-sales-analysis/
│
├── Data/
│   └── Raw and cleaned datasets
│
├── Notebook/
│   └── Jupyter Notebook for data analysis
│
├── Output/
│   └── Analysis outputs and visualisations
│
├── PowerBI/
│   └── Power BI dashboard files
│
├── README.md
├── requirements.txt
└── LICENSE
```

## 🚀 How to Run the Python Analysis

### 1. Clone the repository

```bash
git clone https://github.com/USMAN907/superstore-sales-analysis.git
```

### 2. Navigate to the project directory

```bash
cd superstore-sales-analysis
```

### 3. Install the required Python packages

```bash
pip install -r requirements.txt
```

### 4. Open the Jupyter Notebook

Navigate to the `Notebook/` folder and open the analysis notebook using Jupyter Notebook or JupyterLab.

```bash
jupyter notebook
```

## 📊 Power BI

The Power BI files are available in the:

```text
PowerBI/
```

folder.

Open the Power BI project in **Microsoft Power BI Desktop** to explore the interactive dashboard.

## 🧠 Skills Demonstrated

This project demonstrates practical experience in:

- Data Cleaning
- Data Preprocessing
- Exploratory Data Analysis
- KPI Development
- Business Intelligence
- Data Visualisation
- Dashboard Development
- Power Query
- DAX
- Python Data Analysis
- Pandas
- Matplotlib
- Seaborn
- Business Insight Generation
- Data Storytelling
- Git & GitHub

## 📌 Future Improvements

Potential extensions to the project include:

- Adding a dedicated **SQL analysis layer**
- Customer segmentation
- Sales forecasting
- Advanced Power BI drill-through analysis
- Additional DAX measures
- Automated data refresh
- More advanced customer and product analytics
- Deployment of the dashboard for wider business use

## 👤 Author

**Muhammad Usman**

MSc Big Data & Business Intelligence

Interested in:

- Data Analytics
- Business Intelligence
- Data Science
- Machine Learning
- AI
- Business Analytics

## 📄 License

This project is licensed under the **MIT License**.
