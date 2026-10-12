# E-commerce Sales & Profitability Analysis

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white) ![Jupyter Notebook](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white) ![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white) ![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=for-the-badge&logo=plotly&logoColor=white)

An exploratory data analysis project using Python and Jupyter Notebook to examine e-commerce sales, profit, product categories, sub-categories, and customer segments using the Sample Superstore dataset.

## Project at a Glance

- **Goal:** Understand what drives sales and profitability, and where high sales do not translate into strong profit.
- **Tools:** Python, Pandas, NumPy, Matplotlib, Seaborn, Plotly, Jupyter Notebook.
- **Primary analysis:** monthly sales/profit trends, category and sub-category performance, customer-segment comparisons, and sales-to-profit relationships.

## Repository Structure

```text
.
├── Ecommerce.ipynb
├── data/
│   └── Sample-Superstore.csv
└── README.md
```

## Business Questions

1. Which months have the highest and lowest sales?
2. Which product categories and sub-categories contribute most and least to sales?
3. How does profit change over time?
4. Which categories and sub-categories are most and least profitable?
5. How do Consumer, Corporate, and Home Office segments compare in sales and profit?
6. Does higher sales volume always lead to higher profit?

## Workflow

1. **Load and inspect:** import the CSV into Pandas and inspect data types, missing values, and duplicates.
2. **Clean and transform:** parse Order Date and derive month-level fields for time-series analysis.
3. **Aggregate:** summarize sales and profit by month, category, sub-category, and customer segment.
4. **Visualize:** use Matplotlib, Seaborn, and Plotly charts to compare trends and performance.
5. **Interpret:** distinguish revenue drivers from profit drivers and investigate loss-making areas.

## Key Findings Reported in the Notebook/Original Project Notes

The original project notes report the following patterns. Re-run the notebook against the included dataset to validate the exact figures and confirm whether the current notebook reproduces them.

- Technology is described as a strong profit contributor.
- Furniture is described as having weaker profitability, with Tables highlighted as a loss-making sub-category.
- Copiers are described as a highly profitable sub-category.
- The Consumer segment is described as contributing the largest sales, while Corporate and Home Office are noted for profit contribution efficiency.
- The project emphasizes that high sales do not necessarily guarantee high profit.

These are qualitative findings recorded in the project notes; no exact metric values are claimed in this README.

## How to Run

1. Clone or download this repository.
2. Open `Ecommerce.ipynb` in Jupyter Notebook, JupyterLab, or VS Code with the Jupyter extension.
3. Install the libraries used by the notebook if needed:

   ```bash
   pip install pandas numpy matplotlib seaborn plotly jupyter
   ```

4. Load the dataset from `data/Sample-Superstore.csv`. If the notebook currently uses a different file path, update that cell to match the folder structure.
5. Run the notebook cells from top to bottom and review the output charts and tables.

## Data File Notes

The repository originally contained `Sample - Superstore(1).csv` and a separate `Sample-superstore.csv` file that is only 1 byte, so it does not appear to be a usable dataset. The full dataset has been placed at `data/Sample-Superstore.csv`; use this file as the intended data source.

## Skills Demonstrated

Python fundamentals, data cleaning, Pandas data manipulation, NumPy, EDA, grouping and aggregation, date/time analysis, charting, and communicating business insights.

## Author

**Asish Kumar Sharma**

- [GitHub Profile](https://github.com/Asissharma5935)
- [LinkedIn](https://www.linkedin.com/in/asish-kumar-sharma-9b4a1731b)
