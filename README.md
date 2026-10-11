# Retail Sales Performance & Profitability Analysis

## Project overview
This project analyzes retail order data to evaluate sales, profit, profit margin, monthly trends, product-category performance, regional performance, customer segments, and the relationship between discounts and profitability. It also includes data-quality checks and rule-based observations to support an AI-assisted analytics workflow.

## Dataset
- **Dataset:** Sample Superstore
- **CSV URL:** https://raw.githubusercontent.com/plotly/datasets/master/superstore.csv
- The dataset is a public sample for learning and portfolio analysis. Verify the source and license/usage terms before any external redistribution.

## Deliverables
- `Abhishek_Retail_Sales_Analysis.ipynb` — complete analysis notebook
- `requirements.txt` — Python dependencies
- `Abhishek_ProjectReport.docx` — project documentation
- `README.md` — setup and project overview

## Technologies used
- Python
- Jupyter Notebook
- pandas and NumPy for data preparation and analysis
- Matplotlib for charts
- Rule-based, data-derived observations to support AI-assisted interpretation

## Setup and run
1. Install Python 3.10+ (recommended) and create a virtual environment.
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Launch Jupyter:
   ```bash
   jupyter notebook
   ```
4. Open `Abhishek_Retail_Sales_Analysis.ipynb` and select **Run All**.

The notebook first looks for a local file named `superstore.csv`. If it is not present, it tries to download the CSV from the URL above. If download fails, download the CSV manually, place it beside the notebook, and name it `superstore.csv`.

## Main analysis questions
- How much sales and profit were generated, and what was the overall profit margin?
- How do sales and profit change month by month?
- Which categories and sub-categories contribute most to sales and profit?
- Which regions and customer segments perform best?
- How do discount levels relate to profit?

## Outputs
The notebook exports:
- `cleaned_superstore_data.csv`
- `kpi_summary.csv`
- `monthly_sales_profit.csv`
- `category_performance.csv`
- `region_performance.csv`

## Data quality and interpretation
The notebook reports missing values, removes exact duplicate rows, parses dates, validates core numeric fields, and excludes rows with invalid date/sales/profit/quantity from the main analysis. The discount-profit relationship is descriptive and should not be interpreted as proof of causation.

## Suggested submission checklist
- Run every notebook cell successfully.
- Review the printed observations and charts; write your own final findings based on the results.
- Ensure all four requested files are included in the submission.
- If the internship portal requires a different naming convention, rename the files to match its instructions.
