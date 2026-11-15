# sales-data-analysis-
End-to-end SQL data analysis of a 200-row multi-region retail sales dataset using Python, Pandas, and SQLite in Google Colab. Covers revenue aggregation, regional performance, relational joins, and correlated subqueries.
# Retail Sales SQL Data Analysis

An exploratory data analysis (EDA) project querying a 200-row retail sales dataset (`sales.csv`) across four product categories (**Clothing, Electronics, Furniture, Grocery**) and four regions (**North, South, East, West**).

## Tech Stack
* **Environment:** Google Colab
* **Language:** SQL (SQLite3) & Python
* **Libraries:** `pandas`, `sqlite3`

## Key Analytical Queries Covered
* **Revenue & Volume Aggregations:** Regional and category-level revenue breakdowns (`SUM`, `AVG`, `COUNT`, `GROUP BY`, `HAVING`).
* **Data Validation:** Inline arithmetic checks comparing `quantity * unit_price` against recorded `total_price`.
* **Relational Joins:** Normalized flat sales records into `orders_subset` and `customer_info` tables to execute `INNER JOIN`, `LEFT JOIN`, and `SELF JOIN` operations.
* **Subqueries:** Implemented scalar, multi-row (`IN`), derived-table (`FROM`), and correlated subqueries to benchmark orders against regional and global averages.

## How to Run
1. Open the `.ipynb` notebook in **Google Colab** (click the *"Open in Colab"* badge at the top of the notebook).
2. Upload `sales.csv` to the Colab session storage.
3. Run all cells sequentially to initialize the in-memory SQLite database and execute the queries.
