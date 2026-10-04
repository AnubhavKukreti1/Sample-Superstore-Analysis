🛒 Superstore Sales Analysis
<p align="center"> <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=24&pause=1000&color=36BCF7&center=true&vCenter=true&width=700&lines=Exploring+Superstore+Sales+Data;Turning+Data+into+Business+Insights;Python+%7C+Pandas+%7C+Seaborn+%7C+Matplotlib;EDA+%7C+Sales+%7C+Profit+%7C+Customers" alt="Typing SVG" /> </p> <p align="center"> <img src="https://img.shields.io/badge/Python-3.x-3776AB?style=for-the-badge&logo=python&logoColor=white" /> <img src="https://img.shields.io/badge/Pandas-EDA-150458?style=for-the-badge&logo=pandas&logoColor=white" /> <img src="https://img.shields.io/badge/NumPy-Analysis-013243?style=for-the-badge&logo=numpy&logoColor=white" /> <img src="https://img.shields.io/badge/Matplotlib-Visualization-11557C?style=for-the-badge" /> <img src="https://img.shields.io/badge/Seaborn-Visualization-4C72B0?style=for-the-badge" /> <img src="https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white" /> </p> <p align="center"> <b>📊 An exploratory data analysis project that turns Superstore sales data into actionable business insights.</b> </p> <p align="center"> <a href="#-project-overview">Overview</a> • <a href="#-analysis-workflow">Workflow</a> • <a href="#-visualizations">Visualizations</a> • <a href="#-key-findings">Findings</a> • <a href="#-how-to-run">Run</a> </p>
👨‍💻 Author
<p align="center">
Anubhav Kukreti

BCA — Artificial Intelligence & Data Science
Graphic Era Deemed University

<a href="https://github.com/AnubhavKukreti1"> <img src="https://img.shields.io/badge/GitHub-AnubhavKukreti1-181717?style=for-the-badge&logo=github" /> </a> </p>
🚀 Project Overview

This project performs a complete Exploratory Data Analysis (EDA) on Superstore sales data.

The objective is not simply to create charts, but to answer real-world business questions:

💰 Which products generate the most profit?
🌎 Which regions perform best?
🏆 Which customers contribute the most revenue?
📉 How do discounts affect profitability?
🚚 Which shipping methods provide the best cost/speed trade-off?
📈 Are high-sales products always highly profitable?

The analysis follows the complete data-analysis pipeline:

Raw Data
   ↓
Data Cleaning
   ↓
Data Exploration
   ↓
KPI Calculation
   ↓
Statistical Analysis
   ↓
Visualization
   ↓
Business Insights

📦 Dataset

The dataset contains:

<div align="center">
📌 Attribute	🔢 Value
Rows	8,399
Columns	21
Orders	Sales & shipping records
Customers	Customer-level information
Products	Product & category information
Geography	Province & region
Financials	Sales, profit, discount & shipping cost
</div>
🗂️ Important Columns
Category	Columns
🧾 Order Information	Order ID, Order Date, Order Quantity
💰 Financials	Sales, Profit, Discount, Shipping Cost, Product Base Margin
🚚 Shipping	Ship Mode, Ship Date
👤 Customer	Customer Name, Customer Segment
🌎 Location	Province, Region
📦 Product	Product Category, Sub-Category, Product Name
🛠️ Tech Stack
<p align="center"> <img src="https://skillicons.dev/icons?i=python,numpy,pandas,matplotlib" /> </p>
Tool	Purpose
🐍 Python	Core analysis
🐼 Pandas	Data manipulation
🔢 NumPy	Numerical analysis
📊 Matplotlib	Data visualization
🎨 Seaborn	Statistical visualization
📓 Jupyter Notebook	Interactive analysis
🔍 Analysis Workflow
01 — 🧹 Data Cleaning

Inspected dataset structure

Checked data types

Identified missing values

Converted date columns

Prepared data for analysis

02 — 📊 KPI Analysis

Calculated important business metrics:

💰 Total Sales
💵 Total Profit
📈 Profit Margin
📦 Units Sold
🧾 Order Count
🚚 Shipping Cost

03 — 📈 Time-Series Analysis

Analyzed:

Monthly sales

Monthly profit

Seasonal patterns

Sales growth

Profit trends

04 — 📦 Product Analysis

Investigated:

Product categories

Sub-categories

Best-selling products

Most profitable products

High-sales / low-profit products

05 — 🌎 Regional Analysis

Compared:

Regions

Provinces

Sales

Profit

Profit margins

06 — 👤 Customer Analysis

Identified:

Top customers by sales

Top customers by profit

Customer segments

Revenue concentration

Potential Pareto / 80-20 patterns

07 — 📉 Discount Analysis

Studied the relationship between:

Discount
   ↓
Sales
   ↓
Profit
   ↓
Profit Margin


The goal is to determine whether increasing discounts actually creates additional value or simply reduces profitability.

08 — 🚚 Shipping Analysis

Compared shipping methods based on:

Shipping cost

Delivery time

Order volume

Overall trade-offs

09 — 🔥 Correlation Analysis

Explored relationships between numerical variables using:

Correlation matrices

Scatter plots

Heatmaps

Distribution plots

📊 Visualizations

The project includes a variety of visualizations:

<p align="center">

📊 Bar Charts   
📈 Line Charts   
📦 Box Plots   
🔵 Scatter Plots

<br><br>

🔥 Heatmaps   
📉 Histograms   
🥧 Pie Charts   
📊 Distribution Plots

</p>

The visualizations are designed to answer business questions rather than simply decorate the notebook.

📸 Project Preview

💡 Add screenshots of your strongest visualizations here.

<p align="center"> <img src="visualizations/sales_trend.png" width="80%" /> </p> <p align="center"> <img src="visualizations/profit_by_category.png" width="45%" /> <img src="visualizations/regional_sales.png" width="45%" /> </p> <p align="center"> <i>Sales trends, category performance and regional analysis</i> </p>
📌 Key Findings

⚠️ Replace the placeholders below with the actual numbers calculated in your notebook.

💰 Sales vs Profit

📈 High sales do not necessarily mean high profitability.

Identify products/categories with high revenue but weak margins.

Highlight the products that generate both strong sales and strong profit.

📉 Discount vs Profit

Analyze how profitability changes as discounts increase.

Identify the discount level where profit begins to decline significantly.

Determine whether aggressive discounting is sustainable.

📦 Category Performance

Compare sales and profit across product categories.

Identify the strongest and weakest sub-categories.

Highlight categories with unusually high or low margins.

🌎 Regional Performance

Identify the region generating the highest sales.

Identify the region generating the highest profit.

Compare regional profit margins.

📅 Seasonal Trends

Identify peak sales months.

Identify periods of declining sales.

Investigate whether sales show seasonal patterns.

👤 Customer Concentration

Identify the top customers by sales.

Identify the top customers by profit.

Check whether a small number of customers contribute a large share of revenue.

🚚 Shipping Trade-offs

Compare shipping speed across shipping modes.

Compare shipping costs.

Determine whether faster shipping creates a meaningful cost increase.

📁 Project Structure
Superstore-Sales-Analysis/
│
├── 📂 data/
│   └── Superstore_Sales.csv
│
├── 📂 notebooks/
│   └── ecommerce_analysis.ipynb
│
├── 📂 visualizations/
│   ├── sales_trend.png
│   ├── profit_by_category.png
│   ├── regional_sales.png
│   └── ...
│
├── 📄 README.md
├── 📄 requirements.txt
└── 📄 .gitignore


⚠️ Make sure the structure above matches your actual repository before pushing.

⚡ How to Run
1️⃣ Clone the repository
git clone https://github.com/AnubhavKukreti1/Sample-Superstore-Analysis.git

2️⃣ Enter the project directory
cd Superstore-Sales-Analysis

3️⃣ Install dependencies
pip install -r requirements.txt

4️⃣ Launch Jupyter Notebook
jupyter notebook

5️⃣ Run the analysis

Open:

notebooks/ecommerce_analysis.ipynb


Then run all cells from top to bottom.

📦 Requirements

Your requirements.txt can contain:

numpy
pandas
matplotlib
seaborn
jupyter


Or install everything directly:

pip install numpy pandas matplotlib seaborn jupyter

🎯 Business Questions

This project attempts to answer:

┌─────────────────────────────────────────────┐
│             BUSINESS QUESTIONS              │
├─────────────────────────────────────────────┤
│ 💰 Which products are most profitable?      │
│ 📈 Which categories drive revenue?          │
│ 🌎 Which regions perform best?              │
│ 👤 Who are the most valuable customers?     │
│ 📉 Does discounting hurt profitability?     │
│ 🚚 Which shipping mode is most efficient?   │
│ 📅 When are sales highest?                  │
│ 🔥 What variables are strongly correlated?  │
└─────────────────────────────────────────────┘

🧠 What I Learned

Through this project, I practiced a complete Exploratory Data Analysis workflow in Python:

Data Collection
      ↓
Data Cleaning
      ↓
Data Transformation
      ↓
Exploratory Analysis
      ↓
Visualization
      ↓
Statistical Relationships
      ↓
Business Interpretation


The biggest takeaway was:

High sales do not automatically mean high profitability.

Looking at revenue and profit together provides a much better understanding of business performance.

🚀 Future Improvements

Possible next steps:

 Build an interactive Power BI dashboard

 Add advanced customer segmentation

 Perform RFM analysis

 Build sales/profit forecasting models

 Add automated KPI reporting

 Investigate outliers

 Build a Streamlit dashboard

 Add machine-learning-based sales prediction

⭐ Support

If you found this project useful:

<p align="center">

⭐ Star this repository
🍴 Fork it
💬 Share your feedback

</p>
<p align="center"> <img src="https://capsule-render.vercel.app/api?type=waving&color=36BCF7&height=120&section=footer" /> </p> <p align="center"> <b>Made with 🐍 Python & 📊 Data</b> <br> <i>Turning data into decisions.</i> </p>
