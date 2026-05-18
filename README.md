## Project: Exploratory Data Analysis (EDA) Workbook

**Objective:** Build a reusable multi-sheet exploration tool for sales data.

**Sheets Created:**

1. **Customer Analysis**
   - Customer count by Region and Segment
   - Average sales per customer (LTV proxy)
   - Identified West region as highest customer concentration (358)

2. **Product Analysis**
   - Sales, Profit, and Profit Margin by Category & Sub-Category
   - Color-coded (Red = Loss, Green = Profit)
   - Found 8 sub-categories operating at a loss

3. **Channel Analysis**
   - Sales and Profit per Order by Ship Mode
   - Standard Class drives highest sales but lower profit per order

**Interactive Features:**
- Click any row in Customer sheet → Filters Product and Channel sheets
- Click any product → Filters Customer and Channel sheets
- Cross-sheet filtering enables root cause exploration

**Key Insights:**
- Tables sub-category is unprofitable (-$17K)
- West region has most customers (358) but lower avg spend ($217)
- Same Day shipping has highest profit per order but lowest volume

