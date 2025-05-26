## 📅 Day 1 – Data Cleaning (Excel) 
**Task:** Cleaned Sports Store Sales Dataset

### 🧼 Cleaning Steps Done:

1. **Removed Duplicates**
   - Used **Data → Remove Duplicates**

2. **Filled Missing Ratings**
   - Used average rating: `=IF(ISBLANK(H2), average_value, H2)`
   - Dragged formula down using fill handle

3. **Fixed Sport Names**
   - Used `=PROPER()` to fix text casing
   - Used **Find & Replace (Ctrl + H)** to correct misspellings

4. **Formatted Dates**
   - Changed date column to **Short Date format**

5. **Deleted Blank Rows**
   - Filtered and removed empty records

6. **Checked Number Formats**
   - Ensured Sales, Profit, and Cost were in number format


### 📂 File Included
- `sports_sales_cleaned data.xlsx` – Cleaned version of the dataset

