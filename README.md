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
- ✅ Filled missing values for 2021/2022 and 2022/2023 transfer records using data from the `Countries` sheet.
- ✅ Used **Text-to-Columns** to showcase country details cleanly.
- ✅ Reviewed and corrected inconsistencies in the `Season` column using **filters** and **Find and Replace**.
- ✅ Filled in missing `Continent` values using logical lookup references and consistency checks.

---

## 📊 Step 2: Transfer Balance Table

Created a summary table using `SUMIFS` to compute:

> This table helps answer: **Does Europe import or export more players overall?**

---

## 🔍 Step 3: Country-Level Net Transfer Movement

Built a second table calculating:

- Number of incoming and outgoing transfers per European country
- Total spending and revenue on transfers
- Net movement and balance by country

Used a list of unique European countries extracted from the cleaned data.

| Country    | Season     | Transfers In | Transfers Out | Spending (€M) | Revenue (€M) | Net Balance (€M) |
|------------|------------|---------------|----------------|----------------|----------------|------------------|
| Germany    | 2022/2023  | [x]           | [x]            | [x]            | [x]            | [x]              |
| ...        | ...        | ...           | ...            | ...            | ...            | ...              |

---

## 💡 Step 4: Key Insights – Top 5 Spenders (2022/2023)

Identified the **top 5 European countries** by total spending on **incoming transfers** in the 2022/2023 season.

Calculated:
- Total number of incoming transfers
- Total amount spent
- **Average transfer fee per player** = Total Spending / Number of Transfers

### 📈 Visualization

A combo chart was created:
- **Primary Axis**: Number of incoming players
- **Secondary Axis**: Average transfer fee per player (€M)

This helps visualize both **volume** and **value** per country.

![Top 5 Transfers Chart](screenshots/transfer_visualization.png)

---

## 🧠 Excel Features Used

- ✅ Text-to-Columns for showcasing data
- ✅ Filters & Find and Replace for cleaning
- ✅ `SUMIFS`, `COUNTIFS`, and `AVERAGEIFS` for analysis
- ✅ Dynamic PivotTables for summarization
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
