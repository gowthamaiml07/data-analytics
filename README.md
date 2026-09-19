# Retail Sales EDA — Task 1

A beginner-friendly exploratory data analysis (EDA) project for retail sales. It uses Python, pandas, matplotlib, seaborn, and Jupyter Notebook to meet the Task 1 checklist.

## What is included

- Data inspection: shape, data types, preview, and missing-value check
- Numerical descriptive statistics: mean, median, mode, and standard deviation
- Monthly and quarterly revenue line charts
- Customer age-group and gender analysis
- Top 10 products by units sold and revenue by product category
- Numerical correlation heatmap
- A discount-versus-profit-margin chart for an additional business insight
- Written observations after every chart and evidence-based recommendations

## Dataset and attribution

The source spreadsheet is included as `data/Global Retail Solutions company dataset.xlsx`.

- Dataset: **Global Retail Solutions**
- Creator: Patrick Kimunyi
- Source: <https://www.kaggle.com/datasets/patrickkimunyi/global-retail-solutions>
- Downloaded: 19 September 2026
- Licence shown on Kaggle: **Other (specified in description)**

The source contains product category/name, region, sales amount, quantity, order date, customer ID, customer age/gender, sales, discount, and profit. `Sales Amount` and `Sales` are duplicates in this source, so the notebook uses `Sales Amount` as revenue. Findings apply only to this 200-row dataset and are not general retail claims.

## Project structure

```text
retail-sales-eda/
├── data/
│   └── Global Retail Solutions company dataset.xlsx
├── notebooks/
│   └── retail_sales_eda.ipynb
├── README.md
└── requirements.txt
```

## Setup and run

1. Install Python 3.10 or newer.
2. Download or clone this repository.
3. In the project folder, optionally create and activate a virtual environment.
4. Install the packages:

   ```bash
   pip install -r requirements.txt
   ```

5. Start Jupyter:

   ```bash
   jupyter notebook
   ```

6. Open `notebooks/retail_sales_eda.ipynb` and choose **Run All**.

The dataset is included. To replace it with a new download from Kaggle, keep the same filename in `data/` or update `DATA_PATH` in the notebook.

## Submit through GitHub

1. Sign in at [GitHub](https://github.com) and choose **New repository**.
2. Name it `retail-sales-eda-task-1`, choose **Public** unless your course requires private, then create it without adding a README.
3. Open a terminal in this project folder and run:

   ```bash
   git init
   git add README.md requirements.txt data notebooks
   git commit -m "Complete Retail Sales EDA Task 1"
   git branch -M main
   git remote add origin https://github.com/YOUR-USERNAME/retail-sales-eda-task-1.git
   git push -u origin main
   ```

   Replace `YOUR-USERNAME` with your GitHub username. GitHub may ask you to sign in or create a personal access token.

4. Open the repository in your browser and copy the page address. It will look like `https://github.com/YOUR-USERNAME/retail-sales-eda-task-1`.
5. Paste that address into the Task 1 submission form. This is the required **GitHub Repository Link**; do not submit the clone URL ending in `.git`.

## Before submitting

- Verify that the notebook opens on GitHub with its saved outputs and charts.
- Verify that this README renders correctly.
- Make sure the reviewer can access the repository.
- Submit the repository page URL.
"# data-analytics" 
