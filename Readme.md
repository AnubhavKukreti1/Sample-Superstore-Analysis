# 🛒 Superstore Sales Analysis

An exploratory data analysis (EDA) of a Superstore sales dataset using Python — going beyond charts to answer real business questions about sales, profit, customers, regions, shipping, and discounts.

## 👤 Author

**Anubhav Kukreti**
BCA (AI & DS) student at Graphic Era Deemed University

- GitHub: [@AnubhavKukreti1](https://github.com/AnubhavKukreti1)

## 📌 Project Overview

This project works through a complete EDA workflow on Superstore sales data — from cleaning and structuring the raw data to calculating key business metrics and turning the results into actionable insights. The goal isn't just visualization; it's using the data to answer practical business questions such as which regions perform best, how discounts affect profitability, and which customers and products drive the most value.

## 📂 Dataset

The dataset contains **8,399 rows** and **21 columns**, covering orders, customers, products, sales, shipping, and profitability.

Key columns include:

| Category | Columns |
|---|---|
| Order Info | Order ID, Order Date, Order Quantity |
| Financials | Sales, Profit, Discount, Shipping Cost, Product Base Margin |
| Shipping | Ship Mode, Ship Date |
| Customer | Customer Name, Customer Segment |
| Location | Province, Region |
| Product | Product Category, Sub-Category, Product Name |

## 🛠️ Tools Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

## 🔍 Analysis Workflow

- Inspected data structure, types, and handled missing values / date columns
- Calculated overall sales, profit, profit margin, order count, and units sold
- Analyzed sales and profit trends over time
- Compared performance across product categories and sub-categories
- Evaluated regional and provincial performance
- Identified top-performing products and customers
- Analyzed performance by customer segment
- Studied the relationship between discounts and profit
- Examined shipping methods against shipping cost and speed
- Ran correlation analysis across numerical variables
- Built visualizations to communicate findings clearly

## 📊 Visualizations

Built with Matplotlib and Seaborn, including:

- Bar charts
- Line charts
- Histograms
- Box plots
- Scatter plots
- Heatmaps
- Distribution plots
- Pie charts

## 📁 Project Structure

```
Superstore-Sales-Analysis/
│
├── data/
│   └── Superstore_Sales.csv
│
├── notebooks/
│   └── ecommerce_analysis.ipynb
│
├── visualizations/
├── README.md
├── requirements.txt
└── .gitignore
```

> **Note:** Make sure this structure matches your actual repo layout before pushing to GitHub — if your CSV and notebook currently live elsewhere, move/rename them to match, or update the paths above.

## 🚀 How to Run

1. **Clone the repository**
   ```bash
   git clone https://github.com/AnubhavKukreti1/Sample-Superstore-Analysis.git
   cd Superstore-Sales-Analysis
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Launch Jupyter Notebook**
   ```bash
   jupyter notebook
   ```

4. **Open and run**
   Open `notebooks/ecommerce_analysis.ipynb` and run all cells top to bottom to reproduce the analysis.

## 💡 Key Findings

> ⚠️ **To be filled in with real numbers from the notebook.** Replace each bullet below with the specific figure your analysis produces — this is what makes the project credible to a recruiter. Examples of the *format* to aim for:
> - "The West region generated the highest sales at $X, while the Central region had the lowest profit margin at X%."
> - "Profit margin drops from X% to Y% once discounts exceed Z%, based on the discount-vs-profit scatter plot."

Planned findings to confirm and quantify:

- [ ] Relationship between sales and profit (do high-sales products always mean high profit?)
- [ ] Effect of discount level on profitability
- [ ] Category / sub-category performance differences
- [ ] Regional differences in sales and profit
- [ ] Seasonal or monthly sales trends
- [ ] Share of revenue from top customers (e.g., Pareto/80-20 pattern)
- [ ] Shipping method trade-offs (cost vs. speed)

## 🎯 What I Learned

Through this project, I practiced a full exploratory data analysis workflow in Python — loading and cleaning data, calculating KPIs, building visualizations, and translating results into business insights. A key takeaway: high sales don't automatically mean high profitability, which is why looking at both metrics together matters when evaluating business performance.
