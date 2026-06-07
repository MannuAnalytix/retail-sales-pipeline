# End-to-End Regional Sales Analysis & ETL Quality Pipeline

## 📊 Business Problem & Project Scope
In modern enterprise operations, transactional matrices are frequently distributed across unlinked relational sheets and riddled with data entry anomalies. This project establishes an institutional-grade data engineering pipeline that programmatically extracts, transforms, and standardizes **64,104 transactional records** across multiple backend sheets. By implementing strict validation gates, the data pipeline guarantees 100% computational integrity before archiving a processed master database tier to feed interactive executive dashboards.

## 🛠️ Technical Architecture & Infrastructure
* **ETL & Data Validation Engine:** Python 3.x (Pandas, NumPy, Matplotlib, Seaborn)
* **Execution Environment:** Google Colab Cloud Runtime
* **Hardened Data Warehouse Layer:** Multi-Sheet Excel OpenPyXL Tier (14.1 MB Production Archive)
* **Business Intelligence Interface:** Power BI Desktop Application
* **Executive Presentation Layer:** Microsoft PowerPoint Management Deck

## 🛡️ Pipeline Quality Controls & Feature Engineering
Rather than executing basic processing blocks, this script treats data cleaning as a continuous development lifecycle:
1. **Relational Table Consolidations:** Programmatically maps case-insensitive left-joins connecting unlinked sales ledgers with customer directory indexes, product descriptions, and state region boundaries.
2. **Granular Temporal Deconstruction:** Converts object strings into native Datetime structures to extract separate tracking fields for Year, Month Number, Month Name, and Day of Week to monitor seasonality.
3. **Financial Vector Logic:** Implements vector arithmetic to derive `calculated_revenue`, `total_calculated_cost`, `net_profit`, and `profit_margin_pct` across all rows in memory.
4. **Outlier Quarantine Controls:** Automatically isolates incomplete data anomalies (such as partial 2018 logs) to protect downstream year-over-year reporting symmetry.

## 📂 Repository Directory Layout
* `notebooks/` : Contains `Regional_Sales_EDA.ipynb`, the full 11-cell data profiling and visualization script.
* `data/` : Hosted securely in a unified Google Drive cloud folder containing the raw inputs, the final 14.1 MB engineered spreadsheet database, the interactive Power BI dashboard application, and the PowerPoint executive slide deck.

## 🚀 Execution Guide
1. Open the notebook in Google Colab and run Cell 1 to establish a secure cloud mount to Google Drive.
2. Run the pipeline sequentially to execute left-joins, run defensive data cleaning gates, and generate Seaborn visualization matrices.
3. Locate the output file `sales_report(EDA exported).xlsx` generated inside your workspace directory to instantly populate visual dashboard reports.
