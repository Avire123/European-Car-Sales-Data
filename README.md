# 🚗 Global Electric Vehicle Market Analysis

> **Exploring EV market distribution, vehicle specifications, customer segments, charging options, and promotional pricing using Python.**

![Python](https://img.shields.io/badge/Python-3.x-3776AB?logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-11557C)
![Seaborn](https://img.shields.io/badge/Seaborn-Visualization-4C72B0)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?logo=jupyter&logoColor=white)

## 📌 Project Overview

This project analyzes a **2023 electric vehicle (EV) market dataset** to understand how EV offerings vary across regions, brands, models, vehicle types, technical specifications, customer segments, charging options, and promotional pricing.

The analysis combines **data cleaning, exploratory data analysis (EDA), statistical summaries, and data visualization** to turn raw vehicle-level data into insights that can support EV market and product strategy.

The dataset contains **275 records and 9 variables**, covering regions including Africa, Asia, Europe, North America, Oceania, and South America.

## 🎯 Objectives

The analysis seeks to answer questions such as:

- How are EV offerings distributed across regions?
- Which brands and models appear most frequently in the dataset?
- What vehicle types are offered by different brands?
- How does battery capacity vary across brands?
- Which customer segments are represented across the EV portfolio?
- How common are fast-charging options?
- How do promotional discounts vary across brands and models?
- What relationships can be observed between product specifications, customer segments, and pricing strategies?

## 🗂️ Dataset

The dataset includes the following variables:

| Column | Description |
|---|---|
| `Date` | Month of the observation |
| `Region` | Geographic market/region |
| `Brand` | EV manufacturer/brand |
| `Model` | Vehicle model |
| `Vehicle_Type` | Vehicle body/type classification |
| `Battery_Capacity_kWh` | Battery capacity in kWh |
| `Discount_Percentage` | Promotional discount percentage |
| `Customer_Segment` | Target customer segment |
| `Fast_Charging_Option` | Whether fast charging is available |

### Dataset Summary

- **Records:** 275
- **Variables:** 9
- **Period:** 2023
- **Battery capacity:** 40–100 kWh
- **Discount range:** 0–20%
- **Missing values:** 0
- **Duplicate records:** 0

## 🔍 Analysis Workflow

### 1. Data Loading & Exploration

The project begins by loading the dataset with Pandas and examining:

- Dataset dimensions
- Column names
- Data types
- Sample records
- Memory usage
- Descriptive statistics

### 2. Data Quality Assessment

Data quality checks include:

- Missing-value analysis
- Duplicate-record detection
- Descriptive statistical analysis
- Validation of the cleaned dataset

The analysis found **no missing values and no duplicate records** in the dataset.

### 3. Exploratory Data Analysis

The notebook investigates several dimensions of the EV market:

#### 🌍 Regional Distribution

EV records are compared across six regions:

- Oceania
- Africa
- North America
- Asia
- South America
- Europe

#### 🏭 Brand & Model Analysis

The project examines:

- Brand representation
- Number of models associated with each brand
- Brand-model combinations
- Distribution of models across the dataset

#### 🚘 Vehicle Types

Vehicle types are analyzed across brands to identify differences in portfolio composition.

#### 🔋 Battery Capacity

Battery capacity is analyzed by brand to understand differences in the technical specifications of EV offerings.

The dataset has an average battery capacity of approximately **69.44 kWh**.

#### 👥 Customer Segments

The analysis explores how EV offerings are distributed across customer segments, including:

- Budget Conscious
- Tech Enthusiast
- Eco-Conscious
- High Income

#### ⚡ Fast Charging

Fast-charging availability is investigated across brands and vehicle types to understand the charging capabilities represented in the dataset.

#### 💰 Discount Analysis

Promotional discount percentages are compared across brands and models.

The average discount in the dataset is approximately **8.54%**, with discounts ranging from **0% to 20%**.

## 📊 Key Metrics

| Metric | Value |
|---|---:|
| Total records | 275 |
| Total variables | 9 |
| Average battery capacity | 69.44 kWh |
| Minimum battery capacity | 40 kWh |
| Maximum battery capacity | 100 kWh |
| Average discount | 8.54% |
| Minimum discount | 0% |
| Maximum discount | 20% |
| Missing values | 0 |
| Duplicate records | 0 |

## 🛠️ Technologies & Libraries

This project was developed using:

- **Python**
- **Jupyter Notebook**
- **Pandas** — data manipulation and analysis
- **NumPy** — numerical operations
- **Matplotlib** — data visualization
- **Seaborn** — statistical visualization
- **SciPy** — statistical analysis

## 📁 Repository Structure

```text
european-ev-market-analysis/
│
├── data/
│   └── test (1).csv
│
├── global-ev-market-analysis.ipynb
├── README.md
├── requirements.txt
└── .gitignore
```

## 🚀 How to Run the Project

### 1. Clone the repository

```bash
git clone https://github.com/Avire123/european-ev-market-analysis.git
cd european-ev-market-analysis
```

### 2. Install the dependencies

```bash
pip install -r requirements.txt
```

### 3. Launch Jupyter Notebook

```bash
jupyter notebook
```

Open:

```text
global-ev-market-analysis.ipynb
```

### 4. Run the notebook

Run the cells from top to bottom to reproduce the analysis and visualizations.

## 💡 Business Value

Although this is an exploratory analysis, the approach demonstrates how EV market data can be used to support business questions around:

- **Market positioning** — understanding how brands and vehicle types are represented across regions.
- **Product strategy** — comparing technical specifications such as battery capacity.
- **Customer targeting** — examining the relationship between products and customer segments.
- **Pricing strategy** — evaluating promotional discount patterns.
- **Product differentiation** — comparing charging capabilities across vehicle portfolios.

## 📈 Skills Demonstrated

This project demonstrates practical skills in:

- Data cleaning and preparation
- Exploratory data analysis
- Descriptive statistics
- Pandas data manipulation
- Grouping and aggregation
- Cross-tabulation
- Data visualization
- Business-oriented analysis
- Communicating analytical findings

## 🔮 Possible Future Improvements

Future versions of the project could extend the analysis by:

- Building an interactive **Power BI or Tableau dashboard**
- Adding additional EV variables such as price, range, horsepower, and charging time
- Performing correlation and hypothesis testing
- Building customer segmentation models
- Applying machine learning to predict customer segment or product attributes
- Adding time-series analysis across multiple years
- Comparing EV market trends with external sales and economic data

## 👤 Author

**John Isaac Mcharo**

Data Analyst | Data Science

GitHub: [@Avire123](https://github.com/Avire123)

---

⭐ If you find this project useful, feel free to explore the notebook and provide feedback.
