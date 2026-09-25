# Amazon Sales Analysis

## Project Overview

The **Amazon Sales Analysis** project focuses on analyzing Amazon sales data to understand sales performance, order patterns, product performance, and other important business metrics.

The project involves data preprocessing, data cleaning, exploratory data analysis, segmentation, and dashboard-based visualization to convert raw sales data into meaningful insights.

---

## Objectives

- Analyze Amazon sales data to understand overall business performance.
- Clean and preprocess the raw sales dataset.
- Analyze sales trends and order patterns.
- Identify top-performing products and categories.
- Analyze different order and fulfilment characteristics.
- Segment the data based on important business attributes.
- Create visualizations to present important findings.
- Generate meaningful insights from the sales data.

---

## Project Workflow

The project follows the following workflow:

**Raw Dataset → Data Cleaning → Data Preprocessing → Exploratory Data Analysis → Data Segmentation → Visualization → Insights**

### 1. Data Collection

The raw Amazon sales dataset was collected and used as the starting point for the analysis.

### 2. Data Cleaning

The dataset was examined and processed to improve data quality and prepare it for analysis.

The cleaning process included:

- Handling missing values
- Removing unnecessary columns
- Checking duplicate records
- Correcting data formats
- Standardizing data where required
- Preparing the dataset for further analysis

### 3. Data Analysis

The cleaned dataset was analyzed to understand different aspects of Amazon sales, including:

- Sales performance
- Order status
- Product categories
- Fulfilment methods
- Sales channels
- Product-level performance
- Customer and geographical information

### 4. Data Segmentation

The data was divided into separate analysis sheets based on important attributes to make the analysis easier and more organized.

The segmented data is available in:

`Amazon_Segmented_Report.xlsx`

### 5. Visualization

The analyzed data was used to create charts and a dashboard for presenting important sales trends and findings in a simple visual format.

---

## Dataset

The project uses an Amazon sales dataset containing information related to orders, products, sales, customers, fulfilment, and shipping.

The original dataset is available in:

`Raw_Dataset_Amazon_Sale_Report.csv`

A processed version of the dataset is available in:

`Amazon_Sale_Report_modified.csv`

---

## Data Analysis

### Sales Analysis

Sales data was analyzed to understand overall sales performance and identify important sales patterns.

### Product Analysis

Product-level analysis was performed to identify products contributing significantly to overall sales and order volume.

### Category Analysis

Different product categories were analyzed to understand their contribution to overall sales and order activity.

### Order Status Analysis

Order status information was analyzed to understand the distribution of different order outcomes.

### Fulfilment Analysis

Different fulfilment methods were compared to understand their role in order processing and sales.

### Sales Channel Analysis

Sales channels were analyzed to understand how orders were distributed across different channels.

### Geographical Analysis

Available geographical information was analyzed to understand the distribution of sales and orders across different locations.

---

## Dashboard

The project includes a dashboard created from the analyzed Amazon sales data.

The dashboard provides a visual overview of important sales metrics, trends, and product/category performance.

### Dashboard Preview

![Amazon Sales Dashboard](Dashboard/Dashboard_Overview.png)

---

## Key Insights

The analysis helps identify:

- Overall sales performance and trends.
- Products with higher sales and order volumes.
- Categories contributing significantly to sales.
- Distribution of different order statuses.
- Fulfilment patterns across orders.
- Sales channel distribution.
- Geographical patterns in sales and orders.

> The specific numerical findings are available in the analysis notebook and dashboard.

---

## Project Files

```text
Amazon-Sales-Analysis/
│
├── Dashboard/
│   └── Dashboard_Overview.png
│
├── Amazon_Dataset.ipynb
│
├── Amazon_Sale_Report_modified.csv
│
├── Amazon_Segmented_Report.xlsx
│
├── Raw_Dataset_Amazon_Sale_Report.csv
│
└── README.md
