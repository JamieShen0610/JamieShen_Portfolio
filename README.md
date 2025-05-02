# Excel Folder Generator

This Python script reads all Excel files in a specified folder and creates a nested folder structure based on the `name_key` column values from each file.

## 📁 What it does

- Loops through all `.xlsx` / `.xls` files in `excel_dir`
- For each file:
  - Creates a base folder named after the file (without extension)
  - Reads the `name_key` column
  - For each `name_key`, creates a subfolder

## 🧩 Requirements

- Python 3.x
- pandas
- openpyxl (for reading `.xlsx` files)

Install with:
```bash
pip install pandas openpyxl
