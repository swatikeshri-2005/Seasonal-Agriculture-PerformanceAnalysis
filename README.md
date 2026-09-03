# 🌾 Seasonal Agriculture Performance Analysis

## 📌 Project Overview

**Seasonal Agriculture Performance Analysis** is a data analytics project that explores agricultural performance across different seasons, geographical regions, farming practices, environmental conditions, resource usage, and economic outcomes.

The project analyzes agricultural data to identify meaningful **seasonal patterns, trends, relationships, variations, and performance differences**. The analysis is performed using Python and documented in a Jupyter Notebook.

---

## 🎯 Objectives

The main objectives of this project are to:

* Explore and understand the agricultural dataset.
* Clean and prepare the data for analysis.
* Analyze agricultural performance across different seasons.
* Compare crop yield and profitability between seasons.
* Examine the impact of irrigation methods on agricultural performance.
* Compare agricultural performance across different states.
* Study relationships between environmental, resource, production, and economic variables.
* Identify unusual patterns and significant observations.
* Generate evidence-based insights and recommendations.

---

## 📊 Dataset

The dataset contains **4,000 agricultural records and 28 variables** covering:

### 🌱 Agricultural Information

* Season
* State
* Crop
* Irrigation Method
* Crop Yield
* Production

### 🌦️ Environmental Conditions

* Rainfall
* Average Temperature
* Humidity
* Soil Moisture

### 💧 Resource Usage

* Water Used
* Water Efficiency
* Fertilizer Usage
* Pesticide Usage

### 💰 Economic Information

* Market Price
* Revenue
* Total Cost
* Profit

### 🦠 Risk Information

* Disease/Pest Risk

---

## 🛠️ Technologies Used

* **Python**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Jupyter Notebook**
* **CSV Dataset**
* **Exploratory Data Analysis (EDA)**
* **Statistical & Correlation Analysis**

---

## 🔍 Analysis Performed

### 1. Data Loading and Exploration

The dataset is loaded and examined to understand:

* Number of records and variables
* Data types
* Missing values
* Duplicate records
* Statistical characteristics

### 2. Data Cleaning

The project performs data preparation including:

* Missing-value handling
* Numerical data cleaning
* Duplicate checking/removal
* Preparation of data for analysis

### 3. Seasonal Agricultural Performance

Agricultural performance is compared across:

* **Kharif**
* **Rabi**
* **Zaid**

Key performance indicators include:

* Yield
* Production
* Revenue
* Cost
* Profit
* Disease/Pest Risk
* Water Efficiency

### 4. Irrigation Method Analysis

Different irrigation methods are compared based on:

* Average yield
* Average profit
* Water consumption
* Water efficiency

The analysis shows that **Drip irrigation has the highest observed average profit** in the supplied dataset.

### 5. State-wise Agricultural Performance

Agricultural performance is compared across states using:

* Yield
* Production
* Revenue
* Total Cost
* Profit

The analysis identifies differences in agricultural profitability between regions.

### 6. Relationship Between Agricultural Variables

Correlation analysis is performed to understand relationships between:

* Rainfall
* Temperature
* Humidity
* Soil Moisture
* Fertilizer
* Yield
* Production
* Market Price
* Cost
* Revenue
* Profit
* Water Usage
* Water Efficiency
* Disease/Pest Risk

Scatter plots are also used to examine relationships such as:

**Yield vs Profit**

**Revenue vs Profit**

**Water Efficiency vs Profit**

---

## 📈 Key Findings

### 🌾 Seasonal Yield

| Season |      Average Yield |
| ------ | -----------------: |
| Kharif | **5.64 tonnes/ha** |
| Rabi   | **5.08 tonnes/ha** |
| Zaid   | **4.67 tonnes/ha** |

Kharif shows the highest average yield in the analyzed dataset.

### 💰 Seasonal Profit

| Season | Average Profit |
| ------ | -------------: |
| Kharif |   **₹178,915** |
| Rabi   |    **₹87,689** |
| Zaid   |   **−₹24,805** |

Kharif has the highest observed average profit, while Zaid has a negative average profit.

### 💧 Irrigation

**Drip irrigation** shows the highest observed average profit at approximately **₹219,626**.

### 🗺️ State Performance

**Punjab and Maharashtra** show the highest average profit among the states in the supplied dataset.

### 🔗 Variable Relationships

Profit shows strong positive associations with:

* Revenue
* Production
* Yield
* Water Efficiency

These relationships represent **association rather than causation**.

---

## 💡 Recommendations

Based on the analysis:

* Focus on seasonal planning using historical performance patterns.
* Consider efficient irrigation methods such as drip irrigation where appropriate.
* Monitor water efficiency to improve resource utilization.
* Analyze regional differences before making agricultural decisions.
* Monitor environmental conditions and disease/pest risks.
* Use data-driven approaches for crop and resource planning.

---

## 📁 Project Structure

```text
Seasonal-Agriculture-Performance-Analysis/
│
├── Seasonal_Agriculture_Performance_Analysis.ipynb
├── seasonal_agriculture_performance_dataset.csv
├── README.md
└── images/
    └── analysis_charts/
```

---

## ▶️ How to Run the Project

### 1. Clone the repository

```bash
git clone <YOUR-GITHUB-REPOSITORY-URL>
```

### 2. Navigate to the project directory

```bash
cd Seasonal-Agriculture-Performance-Analysis
```

### 3. Install required libraries

```bash
pip install pandas numpy matplotlib jupyter
```

### 4. Start Jupyter Notebook

```bash
jupyter notebook
```

### 5. Open

```text
Seasonal_Agriculture_Performance_Analysis.ipynb
```

Run the notebook cells sequentially.

---

## 📓 Notebook

The complete analysis, including data cleaning, exploratory analysis, visualizations, comparisons, correlation analysis, findings, and recommendations, is documented in the Jupyter Notebook.

---

## 🚀 Future Scope

The project can be extended with:

* Seasonal yield and profit prediction
* ANOVA and hypothesis testing
* Multi-year time-series analysis
* Interactive dashboards using **Streamlit or Power BI**
* Weather forecasting
* Market-price forecasting
* Crop recommendation systems
* Anomaly detection for unusual seasonal performance
* Machine-learning-based agricultural prediction

---

## 👥 Potential End Users

* Farmers and farm managers
* Agricultural planners
* Agribusiness stakeholders
* Data analysts and researchers
* Policy and planning teams

---

## 📌 Conclusion

The **Seasonal Agriculture Performance Analysis** project demonstrates how data analytics can be used to understand agricultural performance across seasons, regions, irrigation methods, environmental conditions, and economic factors.

The analysis provides evidence-based insights that can support **better seasonal agricultural planning, resource utilization, and decision-making**.

---

## 👩‍💻 Author

**Swati Keshri**

**Swami Vivekananda University**

**VOIS AICTE Major Project — Batch 1 (2026–2027)**

---

## 📜 Project

**Project Title:** Seasonal Agriculture Performance Analysis

**AICTE STU ID:** STU6a3405ef272f91781794287
