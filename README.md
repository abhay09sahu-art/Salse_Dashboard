# 📊 Sales Dashboard | Power BI

## 🎯 Purpose
- An interactive Power BI dashboard that tracks shop sales across India.
- Shows revenue, profit and customer trends in one clear view.
- Helps spot top states, best categories and profit patterns quickly.

## 🛠️ Tech Stack
- **Tool:** Power BI Desktop, Power Query (M language)
- **Formula & Model:** DAX (AOV = Amount / Quantity, Year/Month/Quarter), one-to-many relationships (Orders ↔ Details, Orders ↔ Date)
- **Format:** `.pbit` template, source data in `.csv`

## 🗂️ Data Source
- Dummy data in two CSV files: `Orders.csv` and `Details.csv`.
- Orders: Order ID, Date, Customer, State, City. Details: Amount, Profit, Quantity, Category, Sub-Category, Payment Mode.
- No real or private data is used.

## ✨ Features
- **4 KPI cards:** Total Amount, Profit, Quantity, Average Order Value.
- **Visuals:** Profit by month and sub-category, sales by state, top customers, category and payment mode split.
- **Slicers:** Filter by Quarter and State, with a clean dark theme.

## 🚀 Walkthrough
- Open `Salse_Dashboard.pbit` in Power BI Desktop.
- Point the file paths to your local `Orders.csv` and `Details.csv`, then click Refresh.
- Use the slicers to explore sales and profit by quarter and state.
