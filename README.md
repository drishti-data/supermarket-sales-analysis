# Supermarket Sales Analysis
## AI + Data: Make Data Intelligent — Masterclass 1

### Submission files
1. `Supermarket_Sales_Analysis.ipynb`
2. `requirements.txt`
3. `Supermarket_Sales_Analysis_Report.docx`
4. `README.md`

### Dataset
Uses the supplied Practice Dataset Excel workbook, especially the `Raw_Data` sheet.

### Run
Keep the Excel dataset in the same folder as the notebook, then run the notebook from top to bottom in Jupyter or Google Colab.

### Cleaning
Exact duplicates are removed for analysis; text categories/regions are standardised; revenue is converted to numeric; mixed date formats are parsed; invalid dates and critical missing values are excluded only where required for a metric; negative quantities are treated as suspicious.

### Main findings
- 1,816 transactions are used in the core analysis after documented filtering.
- Laptop is the highest-revenue product.
- Electronics is the highest-revenue category.
- Pune is the highest-revenue region.
- Repeat customers contribute the majority of revenue.

### Important limitation
Payment method and rating analysis are not included because those columns are not present in the supplied workbook.
