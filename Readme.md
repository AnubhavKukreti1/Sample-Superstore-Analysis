🛒 Superstore Sales Analysis

This project is an exploratory data analysis of a Superstore sales dataset using Python.

I worked with the data to understand how the business is performing in terms of sales and profit, and to find patterns across products, customers, regions, shipping methods, discounts, and time.

The main focus of this project is not just creating charts, but using the data to answer simple business questions and find useful insights.

📂 Dataset

The dataset contains 8,399 rows and 21 columns.

Some of the main columns include:

Order ID and Order Date
Order Quantity
Sales and Profit
Discount
Ship Mode
Customer Name and Customer Segment
Province and Region
Product Category and Sub-Category
Product Name
Shipping Cost
Product Base Margin
Ship Date

The dataset gives information about orders, customers, products, sales, shipping, and profitability.

🛠️ Tools Used
Python
NumPy
Pandas
Matplotlib
Seaborn
Jupyter Notebook
🔍 What I Analyzed

In this project, I explored the data in several areas:

Checked the structure and data types of the dataset
Handled date columns and missing values
Calculated overall sales, profit, profit margin, orders, and units sold
Analyzed sales and profit over time
Compared product categories and sub-categories
Looked at regional performance
Identified top-performing products
Analyzed customer segments
Studied the relationship between discounts and profit
Examined shipping methods and shipping costs
Used correlation analysis to understand relationships between numerical variables
Created different visualizations to communicate the findings
📊 Visualizations

I used Matplotlib and Seaborn to create different types of charts, including:

Bar charts
Line charts
Histograms
Box plots
Scatter plots
Heatmaps
Distribution plots
Pie charts

These visualizations helped me compare categories, identify trends, and understand the relationships between different variables.

📁 Project Structure
Superstore-Sales-Analysis/
│
├── data/
│   └── Superstore_Sales.csv
│
├── notebooks/
│   └── ecommerce_analysis.ipynb
│── visualizations/
├── README.md
├── requirements.txt
└── .gitignore

🚀 How to Run the Project
1. Clone the repository
git clone <https://github.com/AnubhavKukreti1/Sample-Superstore-Analysis.git>
cd Superstore-Sales-Analysis

2. Install the required libraries
pip install -r requirements.txt

3. Start Jupyter Notebook
jupyter notebook


Then open:

notebooks/ecommerce_analysis.ipynb

4. Run the notebook

Run the cells from top to bottom to reproduce the analysis.

💡 Key Findings

Some of the main findings from my analysis include:

Sales and profit are not always directly related. Some products generate high sales but relatively low profit.
Higher discounts can have a negative effect on profitability.
Product performance varies considerably between categories and sub-categories.
Sales and profit are different across regions, showing that geographic performance is not uniform.
Sales change over time, with some months performing better than others.
A relatively small group of customers contributes a significant amount of overall sales.
Shipping methods involve a trade-off between shipping speed and shipping cost.

The exact numbers and visual evidence for these findings are available in the notebook.

🎯 What I Learned

Through this project, I practiced using Python for a complete exploratory data analysis workflow — from loading and cleaning a dataset to calculating KPIs, creating visualizations, and turning the results into business insights.

I also learned how important it is to look at both sales and profit when evaluating business performance. High sales do not necessarily mean high profitability.

🔮 Possible Next Steps

If I continue developing this project, I would like to:

Add RFM analysis for customer segmentation
Build a sales forecasting model
Create an interactive dashboard using Power BI or Tableau
Add more detailed product-level profitability analysis
Automate the data cleaning and analysis process

This version feels more like **a person documenting their own project** rather than a generic project description.

### One thing I'd change as you continue

Don't write findings like:

> "Profit margin declines sharply once discounts exceed roughly 20–30%."

unless your notebook actually demonstrates that with a chart/calculation.

Since you're still doing the analysis, it's better to let the **data determine your final findings**. Once we've finished your analysis, we can replace the "Key Findings" section with specific numbers such as:

> "The West region generated the highest sales at $X, while the Central region had the lowest profit margin at X%."

That will make the GitHub project much stronger because a recruiter can see **specific evidence rather than generic claims**.

Also, your project structure in the README should match your **actual folders**. If your CSV and notebook are currently in different locations, we'll set that up cleanly before you push it to GitHub.