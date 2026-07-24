# Coffee Shop Sales Analysis — March vs April Comparison

A single Jupyter notebook comparing March and April sales for 19 coffee shop products using pandas and matplotlib.

## What it does

Reads a 19-row CSV of coffee shop product sales, computes totals and growth rates per product, identifies top sellers and fastest-growing items, and produces bar charts and pie charts. Pure descriptive analytics — no statistical modeling or predictions.

## Tech stack

Python, pandas, matplotlib, Jupyter

## Files

- `Coffee Shop Sales Analysis.ipynb` — Notebook with 14 cells (all executed successfully)
- `Coffee Shop Sales Analysis.csv` — Dataset (19 products, March vs April sales)
- `Coffee Shop Sales Analysis.pdf` — Exported PDF version

## Status

**Basic EDA exercise.** The notebook runs end-to-end with no errors. The dataset is a manually-created spreadsheet, not from a real coffee shop. Hardcoded absolute file path means you must update the `pd.read_csv()` call to run it on your machine.