# 🧹 Data Cleaning and Preprocessing — Task 1

## 📌 Internship
**ElevateLabs x MSME — Data Analyst Internship**

---

## 📂 Dataset
- **Name:** Superstore Sales Dataset
- **Source:** [Kaggle](https://www.kaggle.com/)
- **Size:** 9,800 rows × 18 columns
- **Columns:** Row ID, Order ID, Order Date, Ship Date, Ship Mode, Customer ID, Customer Name, Segment, Country, City, State, Postal Code, Region, Product ID, Category, Sub-Category, Product Name, Sales

---

## 🎯 Objective
Clean and prepare a raw dataset by handling missing values, removing duplicates, standardizing formats, and renaming columns for consistency.

---

## 🛠️ Tools Used
- Python (Pandas, NumPy)
- Kaggle Notebook

---

## 🔧 Cleaning Steps Performed

| Step | Action | Details |
|------|--------|---------|
| 1 | Explored the data | Checked shape, columns, data types |
| 2 | Checked missing values | Found 11 missing values in Postal Code |
| 3 | Removed duplicates | 0 duplicate rows found |
| 4 | Cleaned column names | Renamed to lowercase with underscores |
| 5 | Filled missing values | Numeric columns → median, Text columns → 'Unknown' |
| 6 | Standardized text | All text columns converted to UPPERCASE |
| 7 | Saved cleaned file | Exported as `cleaned_sales_data.csv` |

---

## 📊 Cleaning Summary

```
Original rows  : 9800
Cleaned rows   : 9800
Duplicates removed  : 0
Missing values fixed : 11 (Postal Code → filled with median)
Columns renamed : All renamed to lowercase with underscores
Text standardized : All text converted to uppercase
```

---

## 📁 Files in this Repository

| File | Description |
|------|-------------|
| `notebook.ipynb` | Kaggle Notebook with full cleaning code |
| `cleaned_sales_data.csv` | Final cleaned dataset |
| `README.md` | Project documentation |

---

## 💡 Key Learnings
- How to identify and handle missing values using `isnull()` and `fillna()`
- How to remove duplicate rows using `drop_duplicates()`
- How to standardize column names and text values
- How to export a cleaned DataFrame to CSV

---

## 👩‍💻 Author
**Vishali S **
Data Analyst Intern — ElevateLabs x MSME
