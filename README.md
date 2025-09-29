# Data Analysis Portfolio Project 3 — Marketing Campaign ROI (Power BI)

## 📌 Project Overview
Interactive Power BI report built to evaluate **marketing campaign performance**, **customer engagement**, and **product spend**.  
Focus: clean modeling inside Power BI (Power Query + Data Model), clear **DAX KPIs**, and business-first visuals.

---

## 🧰 Built With
- **Power BI Desktop** only  
  - Power Query for data cleaning/standardization  
  - Data Model (relationships)  
  - DAX measures for KPIs and ratios  
  - Bookmarks, slicer panel, and drill-through for UX

 ---

## 🗂 Dataset
- Kaggle **Marketing Campaign** (~2.2k rows; one row = one customer).
- Columns include demographics, spend by product, recency, channel interactions, and last campaign response.
- **Assumption for demo KPIs:** constant per-customer placeholders used in the model  
  - `Z_Revenue = 11`  
  - `Z_Cost = 3`  
  These support simple, transparent *Revenue / Cost / Profit* and derived metrics (e.g., ROI) for portfolio demonstration.

---

## 🗺 Report Pages (4)
1. **Overview & KPIs** — headline cards (Revenue, Cost, Profit, ROI, Acceptance %), quick filters, and trend tiles.
<img width="1767" height="993" alt="image" src="https://github.com/user-attachments/assets/5a0a34f2-e48e-4e36-a44e-bc6474ea8b1d" />

2. **Customers & Spend** — cuts by age/education/marital status; product spend mix (Wines/Meat/Fish/etc.); recency and visits.
<img width="1768" height="991" alt="image" src="https://github.com/user-attachments/assets/1f58205f-e018-4068-aa79-daf5c5ebe8f1" />

3. **Campaign Results** — Acceptance %, ROI, and Profit by segments; response lift across demographics.
<img width="1771" height="992" alt="image" src="https://github.com/user-attachments/assets/3e6aa5aa-82df-4680-b448-b6a2c58f7536" />


4. **Channel Performance** — web vs. catalog vs. in-store interactions; purchases by channel; conversion and cost efficiency.
<img width="1769" height="992" alt="image" src="https://github.com/user-attachments/assets/6485b927-6265-4200-b76f-f82732a41693" />

