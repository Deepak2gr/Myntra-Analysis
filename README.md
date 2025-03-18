# Myntra-Analysis

📊 Myntra Sales Data Analysis
🔍 Overview
This project analyzes Myntra's sales data using Python, leveraging Pandas, NumPy, Matplotlib, and Seaborn for data cleaning, exploration, and visualization. The goal is to extract meaningful insights about customer behavior, product sales, and discount effectiveness.

📂 Dataset
The analysis uses three datasets:

dim_products – Product details
dim_customers – Customer information
fact_orders – Order transactions
🛠 Tools & Libraries Used
Pandas – Data manipulation
NumPy – Numerical operations
Matplotlib & Seaborn – Data visualization
📌 Key Steps
Data Loading & Cleaning

Read datasets using pandas.read_excel()
Checked for duplicates & missing values
Created new columns:
Month from the date column
Total Price after applying discounts
Exploratory Data Analysis (EDA)

Used .info(), .describe() for data summary
Merged datasets using pd.merge()
Visualized trends with Matplotlib & Seaborn
Insights & Findings

Sales trends across different months
Customer purchasing behavior
Impact of discounts on total revenue
🚀 How to Run the Notebook
Install dependencies:
bash
Copy
Edit
pip install pandas numpy matplotlib seaborn openpyxl
Open the Jupyter Notebook:
bash
Copy
Edit
jupyter notebook
Run all cells and explore the analysis!
📢 Conclusion
This project highlights the power of data analytics in understanding e-commerce trends and customer behavior. Feel free to contribute or share your insights! 🚀
