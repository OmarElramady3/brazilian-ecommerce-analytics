# Brazilian E-commerce Analytics – Power BI Project

## 🔍 Project Overview
Analysis of the **Olist Brazilian E-commerce dataset (2016–2018)**.  
The project delivers insights on **revenue, customers, and sellers** through interactive Power BI dashboards.

---

## 📊 Dashboards
- **Executive Overview** – Revenue, Orders, AOV, Reviews, Order Status, Top Categories  
- **Customer Churn** – One-time vs Repeat customers, Churn ≈ 88%, Repeat ≈ 12%  
- **Sellers Performance** – Active sellers, Avg orders per seller, Revenue by state/city  

📸 Screenshots are available in the `Screenshots/` folder.  
📂 The full Power BI file is in `Dashboards/`.

---

## 🚀 Key Insights
- Total Revenue ≈ **$14M** from 99K orders  
- **88% churn**: most customers purchased only once  
- São Paulo is the dominant market  
- A small number of sellers drive most of the revenue  

---

## 🛠️ Data Preparation & Modeling
- Raw CSVs were cleaned using **SQL (PostgreSQL)**:
  - Removed duplicates and standardized product categories  
  - Normalized date fields  
  - Built a **star schema** with fact & dimension tables  
- Power BI connects to the DWH and uses **DAX measures** for KPIs

---

## 📂 Repository Contents
- `Dashboards/` → Power BI file (`.pbix`)  
- `Screenshots/` → Images of dashboards  
- `Brazilian Olist.pbix` → Main PBIX file  

---

## ✍️ Author
**Omar Elramady – Data Analyst**  

- 📧 Email: [omarelramady44@gmail.com](mailto:omarelramady44@gmail.com)  
- 💼 LinkedIn: [linkedin.com/in/omar-elramady](https://www.linkedin.com/in/omar-elramady/)  
- 🌍 Upwork: [upwork.com/freelancers/~015ea80b7a8fe578f9](https://www.upwork.com/freelancers/~015ea80b7a8fe578f9?mp_source=share)  
