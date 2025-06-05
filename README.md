# 📊 NPTEL 2025 Course Filter

This project provides a simple data processing script using Python (Pandas) to filter and extract relevant NPTEL courses for the July–December 2025 semester.

## 🔍 Objective

To extract **12-week** NPTEL courses related to **Computer Science and Engineering** that are suitable for **UG students** from the official NPTEL course list Excel file.

## 📂 Files

- `NPTEL 2025.ipynb`: Jupyter Notebook with the data filtering logic.
- `Final Course List (July - Dec 2025).xlsx`: Source file (not included here).
- `output.xlsx`: Output file containing the filtered course data.

## ⚙️ How It Works

1. Loads and cleans the original Excel file.
2. Filters courses where:
   - Discipline contains "Computer Science and Engineering"
   - Duration is "12" weeks
   - Course level is "UG"
3. Exports the result to an Excel file.

## 📌 Requirements

- Python 3.x
- `pandas`
- `openpyxl` (for Excel file handling)

## 🚀 How to Run

```bash
pip install pandas openpyxl
🧠 Use Cases
College students planning their NPTEL schedule.

Academic coordinators filtering course data.

Data enthusiasts analyzing trends in NPTEL offerings.

✍️ Author
Prince Patek
