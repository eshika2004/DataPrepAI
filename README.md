# DataPrepAI – Automated Dataset Analysis & Reporting System

## 📌 Overview

**DataPrepAI** is a Python-based automated dataset analysis and reporting system. It analyzes a dataset to provide insights about its **structure, data quality, statistical properties, distributions, and relationships between numerical variables**.

The system does not modify or clean the original dataset. Instead, it **detects, analyzes, explains, and reports** the characteristics of the data.

---

## 🎯 Objective

The main objective of DataPrepAI is to automate the initial stage of data analysis.

Instead of manually performing multiple analysis steps, the user can provide a dataset and automatically receive:

* Dataset overview
* Data quality analysis
* Statistical analysis
* Distribution analysis
* Correlation analysis
* Visualizations
* PDF report

---

## ⚙️ How It Works

```text
Upload Dataset
      ↓
Dataset Overview
      ↓
Data Quality Analysis
      ↓
Statistical Analysis
      ↓
Distribution Analysis
      ↓
Relationship / Correlation Analysis
      ↓
PDF Report
```

---

## 🔹 Modules

### 1. Dataset Overview

Provides basic information about the dataset:

* Number of rows and columns
* Column names
* Data types
* Dataset preview
* Basic dataset summary

### 2. Data Quality Analysis

Checks the quality of the dataset by detecting:

* Missing values
* Duplicate records
* Outliers using the IQR method
* Constant columns

It also provides recommendations for suitable missing-value handling techniques without modifying the dataset.

### 3. Statistical Analysis

Performs statistical analysis based on column type.

**Numerical columns:**

* Count
* Mean
* Median
* Standard deviation
* Minimum
* Q1
* Q3
* Maximum
* Range

**Categorical columns:**

* Count
* Unique values
* Most frequent value
* Frequency

### 4. Distribution Analysis

Analyzes how values are distributed within individual columns.

* Histograms for numerical columns
* Bar charts for categorical columns
* Mean, median, and skewness for numerical distributions

### 5. Relationship / Correlation Analysis

Analyzes relationships between numerical variables using:

* Correlation matrix
* Strongest positive relationship
* Strongest negative relationship
* Weakest relationship
* Correlation heatmap

### 6. PDF Report Generation

All analysis results and visualizations are combined into a **downloadable PDF report**.

The report contains the outputs from all major modules in one place.

---

## 🛠️ Technologies Used

* **Python**
* **Pandas** – Data analysis and manipulation
* **NumPy** – Numerical operations
* **Matplotlib** – Data visualization
* **ReportLab** – PDF report generation

---

## ✨ Key Features

* Automated dataset analysis
* Supports numerical and categorical data
* Data quality checking
* Outlier detection using IQR
* Statistical analysis
* Distribution visualization
* Correlation analysis
* Missing-value technique recommendations
* Automated PDF report generation
* Does not modify the original dataset

---

## 📊 Output

The system generates a comprehensive PDF report containing:

* Dataset information
* Data quality results
* Statistical tables
* Distribution graphs
* Correlation results
* Correlation heatmap
* Missing-value recommendations

Example output file:

```text
DataPrepAI_Report.pdf
```

---

## 🚀 How to Run

### 1. Install the required libraries

```bash
pip install pandas numpy matplotlib reportlab
```

### 2. Run the Python program

```bash
python DataPrepAI.py
```

### 3. Provide the dataset path when prompted.

The system will analyze the dataset and generate the PDF report.

---

## 🔮 Future Scope

Possible future improvements include:

* Support for more file formats
* Advanced statistical tests
* Automatic data-type detection for encoded categorical variables
* More visualization options
* Interactive dashboard
* Web-based interface
* More advanced automated insights

---

## 👩‍💻 Project Purpose

DataPrepAI was developed to understand and automate the **initial exploratory data analysis workflow** using Python. The project combines multiple data-analysis techniques into a single automated system and generates a structured report for easier interpretation.

---

## 📄 License

This project is developed for educational and project purposes.
