# ⚽ European Football Transfers Excel Analysis (2021/2022 & 2022/2023)

This Excel project showcases my ability to **clean raw data**, **extract insights**, and **visualize results** using built-in Excel tools and formulas. The analysis focuses on European football transfers during the 2021/2022 and 2022/2023 seasons.

---

## 📁 Project Structure

- `Football_data_source_RAW.xlsx`: Contains the raw transfer data and country reference information.
- `Football_Transfers_Analysis.xlsx`: Final Excel workbook including cleaned data, tables, analysis, and visualizations.
- `screenshots/`: Folder containing images of key tables and charts for preview.

---

## 🧹 Step 1: Data Cleaning

Performed in Excel using the **Database** and **Countries** sheets from the source file.

Tasks completed:
- ✅ Cleaned and separated unstructured country data in the `Countries` sheet using **Text-to-Columns**, making the data usable for lookups and analysis.
- ✅ Formatted numerical data to improve clarity — including applying currency formats to transfer fees and using comma separators for large numbers.
- ✅ Populated missing values in the `Database` sheet for the 2021/2022 and 2022/2023 seasons by referencing the cleaned data in the `Countries` sheet.
- ✅ Reviewed and corrected inconsistencies in the Season column using **Filters** and **Find and Replace** to standardize year formats.
- ✅ Used **XLOOKUP** and **INDEX-MATCH** formulas to dynamically match and fill missing Continent values in the `Database` sheet based on country information.




---

## 📊 Step 2: Transfer Balance Table

Created a summary table using `SUMIFS` to compute the number of incoming and outgoing football transfers in Europe across the 2021/2022 and 2022/2023 seasons:

![Capture](https://github.com/user-attachments/assets/62bcd93c-c823-4b3f-a074-770f397a60cf)


> This table helps answer: **Does Europe import or export more players overall?**

---

## 🔍 Step 3: European Country Net Transfer Movement & Net Balance

Built a second table calculating:

- Number of incoming and outgoing transfers per European country
- Total spending on incoming and outgoing transfers
- Net movement and balance by European country

Used a list of unique European countries extracted from the cleaned data.

![Capture3](https://github.com/user-attachments/assets/bce3a8ec-9dff-45f0-be6c-efd2b2821dfb)

---


## 💡 Step 4: Key Insights – Top 5 Spenders (2022/2023)

Identified the **top 5 European countries** by **incoming transfers** in the 2022/2023 season.

Calculated for each of the top countries:
- Total number of incoming transfers
- Average Transfer Fee per Player
- **Average transfer fee per player** = Total Transfer Spending / Number of Incoming Transfers

✅ Used `SUMIF` to calculate total transfer spending for each respective country

✅ Used the `LARGE` function to dynamically extract the top 5 countries based on total incoming transfers.


### 📈 Visualization

A combo chart was created:
- **Primary Axis**: Number of incoming players
- **Secondary Axis**: Average transfer fee per player (€M)

This helps visualize both **volume** and **value** per country.

![Capture3](https://github.com/user-attachments/assets/9b9386a3-345e-41a5-9b75-df86b1e6017b)


---

## 🧠 Excel Features Used

- ✅ Text-to-Columns for structuring data
- ✅ Filters & Find and Replace for data cleaning
- ✅ `SUMIFS`, `SUM`, `XLOOKUP`, `INDEX-MATCH`, `IF`, `LARGE` for data analysis and data extraction
- ✅ Combo Charts with dual axes for insights

---

## 📌 Skills Demonstrated

- Data cleaning and preprocessing in Excel
- Creating custom summary tables
- Financial data analysis using formulas
- Data storytelling through visualizations

---

## 📄 Data Source

*This dataset was extracted from a football transfer data collection Excel file, which includes information about countries, seasons, player movements, and transfer fees. For educational use only.*
