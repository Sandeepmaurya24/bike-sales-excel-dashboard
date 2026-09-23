# 🚲 Bike Sales Dashboard (Excel)

An interactive Excel dashboard that analyses bike buyer data to understand **who buys bikes** based on income, commute distance, age and demographics. Built with Pivot Tables, Pivot Charts and Slicers.

> This is my first Excel data analytics project.

---

## 📸 Dashboard Preview

<p align="center">
  <img width="600" alt="Bike Sales Dashboard" src="https://github.com/user-attachments/assets/97a90d17-6e7f-49b1-b2ab-cd345451f375" />
</p>


---

## 🎯 Objective

To answer the question: **What kind of customers are more likely to purchase a bike?**

The dashboard lets the user filter the data by marital status, region and education, and instantly see how the charts change.

---

## 📂 Project Structure

| Sheet | Description |
|-------|-------------|
| `bike_buyers` | Cleaned raw dataset |
| `Working Sheet` | Data preparation and helper columns |
| `Pivot Table` | Pivot tables used as the source for the charts |
| `Dashboard` | Final interactive dashboard |

---

## 📊 Dashboard Components

**Charts**
- **Average Income Per Purchase**: average income by gender, split by purchased bike (Yes / No)
- **Customer Commute**: number of bike purchases by commute distance (0-1, 1-2, 2-5, 5-10, 10+ miles)
- **Customer Age Bracket**: bike purchases across Adolescent, Middle Age and Older customers

**Slicers (interactive filters)**
- Marital Status
- Region
- Education

---

## 🛠️ Tools & Skills Used

- **Microsoft Excel**
- Data cleaning (removing duplicates, standardising values)
- Formulas (`IF` for age brackets)
- Pivot Tables & Pivot Charts
- Slicers for interactivity
- Dashboard design and formatting

---

## 🔍 Process

1. **Data cleaning**: removed duplicates and standardised values (e.g. `M/S` → `Married/Single`, `M/F` → `Male/Female`).
2. **Feature creation**: created an *Age Bracket* column (Adolescent, Middle Age, Older) using an `IF` formula.
3. **Pivot tables**: built pivot tables for income, commute distance and age bracket vs. purchased bike.
4. **Pivot charts**: turned each pivot table into a chart (column and line charts).
5. **Slicers**: connected Marital Status, Region and Education slicers to all pivot tables.
6. **Dashboard**: arranged everything on a single sheet with a clean layout and title banner.

---

## 💡 Key Insights

- Customers who **bought a bike have a higher average income** than those who didn't, for both males (~59.6K vs ~56.5K) and females (~55.3K vs ~53.5K).
- **Short commute distances (0-1 miles)** show the highest number of bike purchases, and purchases generally fall as the distance increases.
- **Middle-aged customers** are the only group where buyers outnumber non-buyers.

*(Insights are based on the unfiltered dashboard view.)*

---

## ▶️ How to Use

1. Download or clone this repository.
2. Open `Excel Project 1.xlsx` in Microsoft Excel.
3. Go to the **Dashboard** sheet.
4. Use the slicers on the left to filter by Marital Status, Region or Education.

```bash
git clone https://github.com/Sandeepmaurya24/bike-sales-excel-dashboard.git
```

---
