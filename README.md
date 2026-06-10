# SQL & Python Data Analysis Project

This project demonstrates an end-to-end data analysis workflow, combining Python for data extraction, cleaning, and preprocessing with SQL for querying and generating business insights.

## Project Structure

- **`orders_data_analysis.ipynb`**: A Jupyter notebook that handles:
  - Downloading the dataset from Kaggle via the Kaggle API.
  - Data cleaning and preprocessing (handling missing values, sorting, and data type conversions).
  - Exporting data for database ingestion.
- **`orders.csv`**: The dataset containing retail order information.
- **`SQL_Analysis.sql`**: A collection of advanced SQL queries designed to answer key business questions.

---

## Getting Started

### Prerequisites

You will need the following installed:
- Python 3.x
- Jupyter Notebook or JupyterLab
- SQL database environment (e.g., PostgreSQL, MySQL, SQLite, or SQL Server)

### Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/vatsalporwal68/SQL_Python_Data_Analysis.git
   cd SQL_Python_Data_Analysis
   ```

2. **Kaggle API Credentials:**
   To download the dataset directly from Kaggle via the notebook, ensure you have your `kaggle.json` API token located in your home directory:
   - **Windows:** `C:\Users\<Username>\.kaggle\kaggle.json`
   - **macOS/Linux:** `~/.kaggle/kaggle.json`

3. **Install Dependencies:**
   ```bash
   pip install pandas kaggle
   ```

4. **Run the Notebook:**
   Open and run the cells in `orders_data_analysis.ipynb` to download and clean the dataset.

---

## SQL Data Analysis Insights

The `SQL_Analysis.sql` file contains queries that run on the processed orders table (`df_orders`) to solve the following business problems:

1. **Top 10 Highest Grossing Products:** Identify which products generate the most revenue.
2. **Top 5 Selling Products per Region:** Breakdown product popularity and sales performance by region.
3. **Month-over-Month (MoM) Growth Comparison:** Compare monthly sales performance side-by-side for 2022 and 2023.
4. **Peak Sales Months per Category:** Identify which months had the highest sales volume for each category of products.
5. **Highest Growth Sub-Category by Profit:** Determine which product sub-category experienced the largest year-over-year profit growth in 2023 compared to 2022.

---

## License

This project is open-source and available under the MIT License.
