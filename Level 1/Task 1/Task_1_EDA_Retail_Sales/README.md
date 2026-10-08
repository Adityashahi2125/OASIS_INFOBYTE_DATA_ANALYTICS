# OASIS INFOBYTE — Data Analytics
## Level 1 — Task 1: EDA on Retail Sales Data

### Objective
Perform exploratory data analysis on retail sales data to identify sales patterns,
customer behaviour and actionable business insights.

### Tech Stack
Python, pandas, matplotlib, seaborn, Jupyter Notebook.

### Folder Structure
```text
Task_1_EDA_Retail_Sales/
├── data/
│   ├── README_DATASET.txt
│   └── retail_sales_dataset.csv        # download from Kaggle
├── notebook/
│   └── Task_1_EDA_Retail_Sales.ipynb
├── output/
│   └── charts/                         # generated when notebook is run
├── requirements.txt
└── README.md
```

### Dataset
Recommended Kaggle source:
https://www.kaggle.com/datasets/mohammadtalib786/retail-sales-dataset

### How to run
1. Download `retail_sales_dataset.csv` from Kaggle.
2. Put it inside `data/`.
3. Open `notebook/Task_1_EDA_Retail_Sales.ipynb` in VS Code/Jupyter.
4. Select your Python/Jupyter kernel.
5. Run **Run All**.
6. Charts will be saved under `output/charts/`.

### Checklist covered
- Dataset loading and inspection
- Shape, dtypes and null-value check
- Mean, median, mode and standard deviation
- Monthly and quarterly sales trends
- Customer age-group and gender analysis
- Product analysis
- Correlation heatmap
- Additional insight visualization
- Written observations after charts
- At least 3 actionable business recommendations
