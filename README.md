# Chocolate Sales Analytics

### An End-to-End Data Analytics Project Using Python, Excel & Power BI

Analyzing chocolate sales data to uncover business insights, evaluate product performance, compare country-wise sales, and understand sales trends through data cleaning, Excel analysis, and interactive Power BI visualizations.

---

## 📌 Project Overview

The Chocolate Sales Analytics project demonstrates an end-to-end data analytics workflow, from raw data cleaning to business analysis and dashboard development.

Python is used to clean and prepare the dataset, Microsoft Excel is used to analyze sales performance through PivotTables, and Power BI is used to create an interactive dashboard.

The same cleaned CSV dataset is used for both Excel analysis and Power BI dashboard development to maintain consistency across the project.

## 🎯 Project Objectives

- Clean and prepare raw sales data using Python.
- Analyze sales performance using Microsoft Excel and PivotTables.
- Develop an interactive Power BI dashboard.
- Identify top-performing products and countries.
- Examine monthly sales trends and sales patterns.
- Answer business questions using data-driven insights.
- Present findings through clear visualizations and business reporting.

## 🧰 Tools & Technologies

| Tool | Purpose |
|---|---|
| Python | Data cleaning and preparation |
| Pandas | Data manipulation and analysis |
| Jupyter Notebook | Executing and documenting the data-cleaning process |
| Microsoft Excel | Sales analysis and PivotTables |
| Microsoft Power BI | Interactive dashboards and data visualization |
| CSV | Storing raw and cleaned datasets |
| GitHub | Project documentation and portfolio presentation |

## 📁 Project Structure

text
chocolate-sales-analytics/
│
├── data/
│   ├── chocolate_sales_raw.csv
│   └── chocolate_sales_cleaned.csv
│
├── python/
│   └── data_cleaning.ipynb
│
├── excel/
│   └── chocolate_sales_analysis.xlsx
│
├── excel_analysis.png
│
├── powerbi/
│   └── chocolate_sales_dashboard.pbix
│
├── dashboard.png
│
└── README.md


## 🔄 Project Workflow

### Step 1: Data Collection

The original chocolate sales dataset is stored in data/chocolate_sales_raw.csv.

### Step 2: Data Cleaning Using Python

The data_cleaning.ipynb notebook is used to inspect, clean, and prepare the raw dataset using Python and Pandas.

### Step 3: Export the Cleaned Dataset

The cleaned dataset is saved as data/chocolate_sales_cleaned.csv.

### Step 4: Excel Analysis

The cleaned CSV dataset is used in Microsoft Excel to create PivotTables and analyze sales by country, product, and salesperson.

### Step 5: Power BI Dashboard Development

The same cleaned CSV dataset is imported into Power BI to create an interactive sales dashboard.

### Step 6: Business Insights

The Excel analysis and Power BI dashboard are used to explore sales performance, identify top-performing products, compare countries, and understand monthly sales trends.

### 📊 Data Flow

*Raw Dataset → Python Data Cleaning → Cleaned CSV → Excel Analysis + Power BI Dashboard → Business Insights*

## 📈 Key Performance Indicators (KPIs)

The project focuses on the following key performance indicators:

| KPI | Value |
|---|---:|
| Total Sales | 6,183,625 |
| Boxes Shipped | 177,007 |
| Sales Records | 1,094 |
| Average Sales per Record | 5,652.31 |
| Countries Covered | 6 |
| Products Covered | 22 |
| Salespeople Included | 25 |
| Analysis Period | January–August 2022 |

Note: These figures are based on the cleaned dataset used in this project. Dashboard KPI cards may display rounded values.

## 📈 Excel Sales Analysis

Microsoft Excel is used to analyze the cleaned dataset through PivotTables.

### Analysis Includes

- *Sales by Country:* Compares total sales and boxes shipped across countries.
- *Sales by Product:* Identifies product-wise sales performance.
- *Sales by Salesperson:* Examines sales contributions by individual salespeople.
- *Product × Country Analysis:* Compares product performance across different countries.

### 🖼️ Excel Analysis Preview

https://github.com/ahamed-irfan-n/chocolate-sales-analytics/blob/main/excel/excel_analysis.png

## 📊 Power BI Dashboard

The Power BI dashboard provides an interactive overview of chocolate sales performance.

### Dashboard Features

- *Total Sales:* Displays the overall sales value.
- *Boxes Shipped:* Shows the total number of boxes shipped.
- *Sales Records:* Displays the number of sales records.
- *Average Sales:* Shows average sales per record.
- *Monthly Sales Trend:* Visualizes monthly sales performance.
- *Sales by Country:* Compares sales across six countries.
- *Top 5 Products by Sales:* Highlights the highest-performing products.
- *Interactive Filters:* Allows users to explore data by country, product, salesperson, and date.

### 🖼️ Dashboard Preview

https://github.com/ahamed-irfan-n/chocolate-sales-analytics/blob/main/powerbi/dashboard.png

## 💡 Business Questions & Insights

This section presents business questions explored through the Excel analysis and Power BI dashboard.

### 1. Which country generates the highest total sales?

*Insight:* Australia recorded the highest total sales among the six countries, with sales of 1,137,367.

*Business Value:* Identifying the strongest-performing market can help businesses evaluate market opportunities and develop sales strategies.

### 2. Which product contributes the most to total sales?

*Insight:* Smooth Sliky Salty was the highest-selling product by sales amount, with total sales of 349,692.

*Business Value:* Identifying top-performing products can help businesses understand product performance and plan inventory and promotional activities.

### 3. How do sales change from month to month?

*Insight:* The monthly sales trend shows variations in sales performance throughout the January–August 2022 analysis period.

*Business Value:* Understanding monthly trends can help businesses recognize stronger and weaker sales periods and plan future sales activities.

### 4. Which salesperson generates the highest sales?

*Insight:* Sales by salesperson can be compared using the Excel PivotTable and Power BI dashboard to identify high-performing salespeople.

*Business Value:* This analysis can support sales performance evaluation, recognition, and targeted training.

### 5. Which products perform well across different countries?

*Insight:* Product sales vary across countries. The Product × Country analysis helps identify products that perform strongly in individual markets.

*Business Value:* Understanding country-level product performance can help businesses tailor product promotions and sales strategies to different markets.

### 6. What is the overall sales performance of the business?

*Insight:* The dataset contains 1,094 sales records, total sales of 6,183,625, and 177,007 boxes shipped.

*Business Value:* These metrics provide an overview of sales activity and help monitor overall business performance.

## 🔍 Key Findings Summary

- *Top Country:* Australia, with total sales of 1,137,367.
- *Top Product:* Smooth Sliky Salty, with total sales of 349,692.
- *Total Sales:* 6,183,625.
- *Total Boxes Shipped:* 177,007.
- *Total Sales Records:* 1,094.
- *Countries Covered:* 6.
- *Products Covered:* 22.
- *Analysis Period:* January–August 2022.

These findings demonstrate how data cleaning, structured analysis, and visualization can turn sales records into meaningful business insights.

## ▶️ How to Use This Project

### 1. Clone the Repository

bash
git clone https://github.com/ahamed-irfan-n/chocolate-sales-analytics.git
cd chocolate-sales-analytics


Replace the repository URL if your actual GitHub repository uses a different name or URL.

### 2. Run the Python Notebook

- Open python/data_cleaning.ipynb using Jupyter Notebook or JupyterLab.
- Ensure the raw dataset is available at data/chocolate_sales_raw.csv.
- Run the notebook cells to clean and prepare the data.
- Verify that data/chocolate_sales_cleaned.csv is generated successfully.

### 3. Open the Excel Workbook

- Open excel/chocolate_sales_analysis.xlsx in Microsoft Excel.
- Review the PivotTables and sales summaries.
- Explore the country-wise, product-wise, and salesperson-wise analysis.

### 4. Open the Power BI Dashboard

- Open powerbi/chocolate_sales_dashboard.pbix using Power BI Desktop.
- If required, update the data source path to data/chocolate_sales_cleaned.csv.
- Refresh the data to view the report.
- Use the available filters to explore sales performance.

## 📂 Files Included

| File | Description |
|---|---|
| data/chocolate_sales_raw.csv | Original chocolate sales dataset |
| data/chocolate_sales_cleaned.csv | Cleaned dataset used for Excel and Power BI |
| python/data_cleaning.ipynb | Python notebook for data cleaning |
| excel/chocolate_sales_analysis.xlsx | Excel workbook containing sales analysis |
| excel_analysis.png | Screenshot of the Excel analysis |
| powerbi/chocolate_sales_dashboard.pbix | Power BI dashboard file |
| dashboard.png | Screenshot of the Power BI dashboard |
| README.md | Project documentation |

## 🎓 Skills Demonstrated

- Data Cleaning and Preparation
- Python and Pandas
- Microsoft Excel Data Analysis
- PivotTables and Data Summarization
- Power BI Dashboard Development
- Data Visualization
- Exploratory Data Analysis
- Business Question Analysis
- Business Intelligence
- Data-Driven Decision Support
- GitHub Project Documentation

## 📚 Data Source and License

### Dataset Information

- *Dataset Name:* Chocolate Sales Dataset
- *Dataset Source:* Kaggle — Chocolate Sales Dataset
- *Original Creator:* Atharva Soundankar
- *Dataset Link:* https://www.kaggle.com/datasets/atharvasoundankar/chocolate-sales

This project uses the Chocolate Sales dataset from Kaggle for educational purposes, data analytics practice, and portfolio development.

The dataset is used to practice data cleaning, sales analysis, business insights, and dashboard development using Python, Microsoft Excel, and Power BI. Credit is given to the original dataset creator.

Please refer to the original Kaggle dataset page for its licensing terms and attribution requirements.

### Project License

The original project materials created for this portfolio project may be released under the MIT License, where applicable.

- *Project License:* MIT License
- *License Information:* https://opensource.org/license/mit

The MIT License applies to my own project materials where applicable and does not automatically apply to the original Kaggle dataset.

The original dataset remains subject to its creator’s licensing terms. Please review those terms before redistributing the original dataset or modified versions of it.

## 👤 Author & Contact

*Ahamed Irfan N*

Aspiring Data Analyst | Python (Pandas,numpy)| SQL | Excel | Power BI

- *GitHub:* https://github.com/ahamed-irfan-n
- *LinkedIn:* https://linkedin.com/in/ahamed-irfan-n-5b5303418

Feel free to explore the project and connect with me.

## 🏁 Conclusion

The Chocolate Sales Analytics project demonstrates an end-to-end data analytics workflow using Python, Microsoft Excel, and Power BI.

It showcases practical skills in data cleaning, data preparation, sales analysis, PivotTables, dashboard development, data visualization, and business reporting.

This project helped me apply data analytics techniques to a sales dataset, derive meaningful business insights, and develop practical skills relevant to an aspiring Data Analyst.
