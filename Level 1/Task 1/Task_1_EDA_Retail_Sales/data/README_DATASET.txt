DATASET REQUIRED FOR TASK 1
=============================

Recommended source:
Kaggle - Retail Sales Dataset
https://www.kaggle.com/datasets/mohammadtalib786/retail-sales-dataset

Expected file:
retail_sales_dataset.csv

Expected columns:
Transaction ID, Date, Customer ID, Gender, Age, Product Category,
Quantity, Price per Unit, Total Amount

Place the downloaded CSV in this folder:
Task_1_EDA_Retail_Sales/data/retail_sales_dataset.csv

IMPORTANT DATASET NOTE
----------------------
The commonly recommended Kaggle Retail Sales Dataset contains product
CATEGORY but does not contain individual product names. Therefore the
"Top 10 best-selling products" requirement cannot be honestly completed
from this exact dataset without inventing product names.

The notebook below handles this transparently:
- If a Product Name/Product column exists, it produces the required Top 10
  product analysis.
- Otherwise it produces the best available product-category analysis and
  documents the limitation in Markdown.

Do not create fake product names just to satisfy the checklist.
