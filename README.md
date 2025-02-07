# ETL_Pipeline_Project
ETL pipeline to process Gartner market share data and visualize results.

# ETL Pipeline for Gartner Market Share Data (2019-2023)
This project automates data extraction, transformation, and loading (ETL) for Gartner's market share data (2019-2023). The processed data is visualized through an interactive dashboard for insights at vendor, market, segment, and country levels.

# Key Components
ETL Pipeline: Extract: Read CSV files (2019-2023).

Transform: Standardized column names (e.g., Vendor.1 → Vendor). Handled missing values & duplicates. Ensured consistent market definitions. Load: Stored cleaned data into an SQLite database.

Data Dashboard: Used Streamlit & Seaborn for visualization. Provided insights on market trends, vendor performance, and M&A activity.

Performance Optimization: Indexed database queries for speed. Batch processing instead of row-by-row insertion. Parallel execution for handling large datasets.

Error Handling & Logging: Logged missing files, incorrect formats, and transformation failures. Used try-except for database transactions.

# Data Pipeline Architecture
Data Flow: 📂 CSV Files → 🔄 ETL Processing → 🗄️ SQLite Database → 📊 Streamlit Dashboard

Technologies Used: Python (pandas, numpy, sqlite3) Streamlit, Seaborn, Matplotlib Google Colab & GitHub

# How to Run the Project
Go to the GitHub repository https://github.com/Nirmit29/ETL_Pipeline_Project/ . Clone the repository, install dependencies, run the ETL pipeline, and launch the dashboard.
