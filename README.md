note: ignore the folder structure as i haven't maintained it due to time constraints

# Superstore-Data-Cleaning-Visualisation
# Data Cleaning & Visualization of Superstore Sales Dataset

## Project Overview

This project focuses on cleaning, preprocessing, analyzing, and visualizing a Superstore Sales dataset using Python. The objective is to transform raw sales data into meaningful business insights through a structured data analytics workflow.

The project demonstrates industry-standard practices in data cleaning, exploratory data analysis (EDA), business intelligence reporting, and dashboard development using Google Colab.

The final output includes data quality improvement, exploratory analysis, professional visualizations, executive-level dashboard reporting, business insights, and strategic recommendations.

---

## Objectives

The primary objectives of this project are:

* Clean and preprocess the Superstore dataset.
* Handle missing values effectively.
* Identify and remove duplicate records.
* Detect and treat outliers using the IQR method.
* Perform Exploratory Data Analysis (EDA).
* Create professional business visualizations.
* Analyze sales and profit performance.
* Identify top-performing and underperforming business segments.
* Build an executive summary dashboard.
* Generate actionable business recommendations.

---

## Project Deliverables

The following deliverables are included in this project:

### Data Cleaning

* Missing value analysis and treatment
* Duplicate record identification and removal
* Data type validation and correction
* Data quality assessment

### Data Preprocessing

* Data formatting and standardization
* Date conversion and feature preparation
* Outlier detection using the IQR method

### Exploratory Data Analysis (EDA)

* Sales analysis
* Profit analysis
* Category and sub-category performance
* Regional and state-wise analysis
* Customer segment analysis
* Shipping mode analysis
* Monthly sales trend analysis

### Data Visualization

* Professional business charts
* Statistical distributions
* Comparative performance visualizations
* Correlation analysis

### Dashboard

* Executive summary dashboard
* KPI reporting
* Regional performance overview
* Category and profit analysis
* Sales trend monitoring

### Business Intelligence Reporting

* Business insights after every major analysis
* Data storytelling approach
* Strategic business recommendations

### Final Deliverables

* Cleaned dataset analysis
* EDA report
* Business dashboard
* Key findings
* Recommendations for decision-makers


## Dataset Information

### Dataset Name

Superstore Sales Dataset

### Dataset Type

Retail Sales Data

### Expected Features

The dataset typically contains:

* Order ID
* Order Date
* Ship Date
* Ship Mode
* Customer ID
* Customer Name
* Segment
* Country
* City
* State
* Region
* Product ID
* Category
* Sub-Category
* Product Name
* Sales
* Quantity
* Discount
* Profit
* Market
* Shipping Cost
* Order Priority

### File Location

```text
data/Superstore.csv
```

---

## Features

### Data Cleaning

* Missing value detection and treatment
* Duplicate record identification and removal
* Data type validation and correction
* Formatting and standardization

### Data Preprocessing

* Date conversion
* Feature preparation
* Data quality checks

### Outlier Analysis

* Boxplot visualization
* Interquartile Range (IQR) method
* Outlier treatment strategy

### Exploratory Data Analysis

* Sales distribution analysis
* Profit distribution analysis
* Category performance analysis
* Sub-category performance analysis
* Regional sales analysis
* State-wise analysis
* Customer segment analysis
* Shipping mode analysis
* Monthly sales trend analysis
* Product performance analysis
* Customer contribution analysis
* Market-wise performance analysis
* Shipping cost analysis
* Order priority analysis
  
### Dashboard Development

* KPI summary
* Regional performance overview
* Category comparison
* Profit analysis
* Monthly trend visualization
* Top product analysis

### Business Intelligence Reporting

* Business insights after every visualization
* Data storytelling approach
* Strategic recommendations

---

## Repository Structure

```text
Superstore-Data-Cleaning-Visualization/
│
├── data/
│   └── Superstore.csv
│
├── notebook/
│   └── Data_Cleaning_Visualization.ipynb
│
├── images/
│   ├── sales_by_region.png
│   ├── monthly_sales.png
│   ├── profit_by_category.png
│   └── dashboard.png
│
├── assets/
│   └── project_banner.png
│
├── requirements.txt
├── README.md
├── .gitignore
├── LICENSE
```

---

## Technologies Used

### Programming Language

* Python

### Libraries

* Pandas
* NumPy
* Matplotlib
* Seaborn

### Development Environment

* Google Colab

### Version Control

* Git
* GitHub

---

## Installation

### Clone the Repository

```bash
git clone https://github.com/SarabjeetKhadka/Superstore-Data-Cleaning-Visualization.git
```

### Navigate to Project Directory

```bash
cd Superstore-Data-Cleaning-Visualization
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

---

## Running in Google Colab

### Step 1

Open Google Colab.

### Step 2

Upload the repository folder to Google Drive or GitHub.

### Step 3

Open:

```text
notebook/Data_Cleaning_Visualization.ipynb
```

### Step 4

Ensure the dataset is located at:

```text
data/Superstore.csv
```

### Step 5

Run all notebook cells sequentially from top to bottom.

---

## Workflow

### 1. Data Loading

Import and load the Superstore dataset.

### 2. Data Exploration

Understand dataset structure and quality.

### 3. Data Cleaning

* Handle missing values
* Remove duplicates
* Validate data types
* Standardize formatting

### 4. Outlier Detection

* Visual inspection using boxplots
* IQR-based outlier identification

### 5. Exploratory Data Analysis

Analyze:

* Sales
* Profit
* Regions
* Categories
* Customers
* Products

### 6. Dashboard Development

Create an executive-level dashboard.

### 7. Business Insights

Generate actionable recommendations.

---

## Business Problem

Retail businesses generate large amounts of transactional data every day. Poor data quality and lack of analysis can prevent organizations from understanding sales performance, customer behavior, and profit drivers.

This project aims to convert raw retail sales data into meaningful insights that support business decision-making through data cleaning, analysis, and visualization.

---

## Key Findings

The notebook investigates:

- Highest revenue-generating categories
- Most profitable product segments
- Regional performance
- Market-wise performance
- Customer purchasing behavior
- Sales seasonality and monthly trends
- Impact of discounts on profitability
- Shipping cost trends
- Order priority contribution
- Top-performing products and customers

Detailed findings are discussed throughout the notebook in dedicated Business Insight sections.

---

## Screenshots

### Project Dashboard

*(Add dashboard screenshot here)*

### Sales Analysis

*(Add sales visualization screenshot here)*

### Regional Performance Analysis

*(Add regional performance screenshot here)*

### Profit Analysis

*(Add profit analysis screenshot here)*

---

## Future Improvements

Potential enhancements include:

* Interactive dashboards using Plotly
* Power BI integration
* Predictive sales forecasting
* Customer segmentation using machine learning
* Automated reporting pipeline
* Deployment as a web application

---

## Author

**Sarabjeet Khadka**

Data Analytics & Business Intelligence Project

Tools Used:

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Google Colab
* GitHub

---

## Conclusion

This project demonstrates a complete end-to-end data analytics workflow including data cleaning, preprocessing, exploratory analysis, visualization, dashboard creation, business storytelling, and strategic recommendations.

The project is designed to simulate a real-world business intelligence scenario and serves as a strong portfolio project for internships, academic submissions, and data analytics roles.
