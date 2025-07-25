# 📈 Startup Expansion Analysis

This project analyzes data from various retail stores to assess the impact of marketing and regional expansion on store revenue. It uses a combination of data exploration, visualization, and statistical insights to guide business decision-making.

---

## 📁 Files in This Repository

### 1. `startup-expansion.xlsx`

This Excel file contains information about individual store performance and related metrics. The dataset includes the following columns:

| Column Name         | Description                                                                 |
|---------------------|-----------------------------------------------------------------------------|
| `Store ID`          | Unique identifier for each store                                            |
| `City`              | City where the store is located                                             |
| `State`             | U.S. state where the store is located                                       |
| `Sales Region`      | Regional sales grouping (e.g., Region 1, Region 2, etc.)                    |
| `New Expansion`     | Indicates whether the store is part of a new expansion (`New` or `Old`)     |
| `Marketing Spend`   | Amount of money spent on marketing for that store (in dollars)              |
| `Revenue`           | Total revenue generated by that store (in dollars)                          |
| `Profit`            | Revenue minus Marketing Spend:<br> `Profit = Revenue - Marketing Spend`     |
| `ROMS%`             | Return on Marketing Spend Percentage:<br> `ROMS% = (Profit / Marketing Spend) * 100` |

---

### 2. `Startup-Expansion.ipynb`

This Jupyter Notebook performs the core analysis of the dataset.

#### ✅ Step-by-Step Analysis

1. **Import Libraries**
   - Uses `pandas`, `numpy`, `matplotlib`, and `seaborn` for data manipulation and visualization.

2. **Load Dataset**
   - Reads the Excel file using `pandas.read_excel()`.

3. **Preview and Explore Data**
   - Uses `.info()` and `.describe()` to understand structure, data types, and distributions.

4. **Create New Metrics**
   - Calculates `Profit` and `ROMS%` to evaluate marketing efficiency.

5. **Visualizations**
   - Analyze revenue vs. marketing spend.
   - Compare performance between new vs. old expansion stores.
   - Regional comparison using plots (bar, scatter, box plots).

6. **Insights**
   - Determine the effectiveness of marketing strategies.
   - Identify high-performing regions or stores.
   - Compare returns between new and existing stores.

7. **New Calculated Metrics**
   - `Profit`: Actual earnings from operations.
   - `ROMS%`: Return on every marketing dollar spent.
8. **Export for Power BI**
   - After performing the analysis and creating new calculated columns (`Profit` and `ROMS%`), the final processed dataset is saved as a CSV file:`expansion_startup_new.csv`
9. **Power BI Dashboard**
    "Startup_Expansion_Dashboard.pdf"
   - Overview
   - States
   - Cities
   - Stores
---

## 🎯 Objective

This project helps stakeholders:

- Evaluate store performance based on marketing investment and regional distribution.
- Make data-driven decisions about future store expansions.
- Understand marketing ROI (Return on Investment).

---

## 🛠 Requirements

Python libraries used in this project:

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- Jupyter Notebook


