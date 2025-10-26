# 🧾 E-Commerce Delivery Performance Analysis Project

## 📘 Overview
This project focuses on analyzing and visualizing **e-commerce delivery performance** to uncover factors that influence delivery efficiency, customer satisfaction, and discount effectiveness.  
The process involves cleaning, transforming, and visualizing data to derive actionable insights that can help **optimize logistics operations** and **enhance customer experience**.

---

## 🎯 Objectives
- Evaluate **on-time delivery performance** across different shipment modes and warehouses.  
- Analyze **customer ratings, product importance**, and **discount impact** on delivery success.  
- Develop an **interactive Power BI dashboard** for performance tracking and decision support.

---

## 🧩 Tools & Technologies Used
- **Python (Jupyter Notebook)** – Data cleaning, preprocessing, and transformation.  
- **Pandas, NumPy** – Data manipulation and feature engineering.  
- **Power BI** – Data modeling, DAX calculations, and dashboard creation.  
- **Power Query (M Code)** – Transformation logic for calculated columns.  
- **Excel** – Cleaned dataset export and validation.

---

## 🧮 Datasets
| File Name | Description |
|------------|-------------|
| `Train.csv` | Raw dataset containing e-commerce order details |
| `Cleaned_Train_File.xls` | Cleaned dataset after preprocessing in Python |
| `E-commerce.ipynb` | Jupyter Notebook used for data cleaning and transformation |
| `ecomus sheet.xlsx` | Transformed dataset post Power Query |
| `E-Commerce Delivery Performance.pbix` | Power BI dashboard file |

---

## 🧱 Steps Involved in Building the Project

### 1. Data Collection
Imported the raw dataset (`Train.csv`) containing e-commerce order details, shipment modes, warehouses, product costs, discounts, and customer ratings.

### 2. Data Cleaning (Python – Jupyter Notebook)
- Handled missing and inconsistent values.  
- Removed duplicates and standardized categorical fields.  
- Created new columns such as:
  - `Discount_Percent`
  - `Gender_Label`
  - `Weight_Bin`
- Exported the cleaned dataset as **Cleaned_Train_File.xls**.

### 3. Data Transformation (Power BI)
- Imported the cleaned dataset and refined data using **Power Query (M Code)**.  
- Created calculated columns:
  - `Weight_Bin` – Categorized products by weight range.  
  - `Discount_Percent` – Computed discount as a percentage of product cost.  
  - `Gender_Label` – Converted gender codes (M/F) to descriptive labels.  

- Created **DAX measures**:
  - `Total Orders`  
  - `On-Time Deliveries`  
  - `On-Time %`  
  - `Average Discount %`  
  - `Average Rating`  
  - `Average Cost`  
  - `Total Discount Amount`

### 4. Visualization (Power BI Dashboard)
Designed 2–3 interactive dashboards focusing on:
- **Delivery Performance** (Shipment mode, warehouse, and trends)  
- **Customer Insights** (Ratings vs. Discounts, Product Importance)  
- **Operational Overview** (On-Time %, Average Discount, Cost KPIs)  

Added **slicers for filters**: Shipment Mode, Warehouse, Product Importance, and Gender.  
Used **KPI cards** and **trend lines** for easy performance tracking.

---

## 📊 Key Insights
- Shipments by **Air** had the highest on-time delivery percentage.  
- **Medium-weight products** experienced the most balanced delivery rates and costs.  
- Customers offered **moderate discounts** tended to give higher ratings.  
- Some **warehouses consistently underperformed**, indicating optimization potential.

---

## 📊 Final Dashboard Preview

<img width="1133" height="636" alt="Screenshot " src="https://github.com/user-attachments/assets/f25faccb-335b-414c-a0d7-820520032db9" />

---

<img width="1133" height="637" alt="Screenshot " src="https://github.com/user-attachments/assets/2face64d-1652-43b0-adc2-72bf7e546662" />

---
## 📂 Repository Structure

- [**Train.csv**](Train.csv) | Raw dataset containing e-commerce delivery details including shipment mode, warehouse block, product cost, discount, and customer ratings.  
- [**Cleaned_Train_File.xls**](Cleaned_Train_File.xls) | Cleaned and processed dataset generated using Python (Jupyter Notebook).  
- [**E-commerce.ipynb**](E-commerce.ipynb) | Jupyter Notebook used for data cleaning, preprocessing, and feature engineering.  
- [**E-Commerce Delivery Performance.pbix**](E-Commerce%20Delivery%20Performance.pbix) | Power BI dashboard file for interactive visual analytics.  
- [**E_Commerce_Delivery_Performance_Project_Report.pdf**](E_Commerce_Delivery_Performance_Project_Report.pdf) | Final professional project report summarizing methodology, tools, and insights.  
- [**README.md**](README.md) | Project documentation, workflow summary, and usage instructions.  


---

## 🧠 Conclusion
This project successfully integrates **Python** and **Power BI** to convert raw e-commerce data into **business intelligence insights**.  
The final dashboard allows management to:
- Monitor delivery performance  
- Optimize shipping methods  
- Enhance customer satisfaction  

By leveraging **data analytics**, the organization can improve operational efficiency and develop **informed logistics strategies**.
