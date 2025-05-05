# 📊 Amazon Monthly Sales Dashboard

### 🔗 Dashboard Link: *(https://drive.google.com/file/d/1_1_AtMtY4U5yKbVsaNUrpb3-p0lVnB76/view?usp=sharing)*

## 🧩 Problem Statement

This Power BI dashboard helps Amazon's sales and operations teams gain critical insights into product performance, customer preferences, and regional sales behavior. With the ability to drill into profit/loss across products and categories, identify high- and low-performing SKUs, and visualize sales trends across geography and time, this dashboard serves as a powerful tool to optimize inventory, marketing strategies, and customer targeting.

---

## 🛠️ Steps Followed

### 1. **Data Preparation**

* Dataset loaded into **Power BI Desktop**.
* Data cleaning and transformation done using **Power Query Editor**.
* Columns were profiled for errors, nulls, and data types.

### 2. **Data Model Structure**

* Built a **star schema** model with clear dimension and fact tables.
* **Fact Table**: `AM_Sales`
* **Dimension Tables**:

  * `Amazon_Products`
  * `Amazon_Customers`
  * `Amazon_Product_Categories`
  * `Amazon_Product_Subcategories`
  * `Amazon_Calendar`
  * `Amazon_Territories`
  * `Amazon_Returns`
  * `Profit_Loss_Toggle`

  
![Image](https://github.com/user-attachments/assets/d103ce1a-85cc-4770-959d-459f3a0962ed)


### 3. **DAX Measures Created**

* **Total Sales**
* **Dynamic Profit/Loss**
* **Top 3 Performers/Losers**
* **Monthly Sales by Date**
* **Profit/Loss Toggle logic**

---

## 📈 Visuals Used

| Visual          | Purpose                                   |
| --------------- | ----------------------------------------- |
| Treemap         | Orders by Category                        |
| Bar Chart       | Orders by Subcategory                     |
| Table           | Profit/Loss by Product                    |
| Line Area Chart | Monthly Profit and Previous Month Sales   |
| Card Visual     | Profit/Loss Toggle                        |
| Map             | Sales Distribution by Region              |
| List            | Top 3 Performing/Underperforming Products |


![Image](https://github.com/user-attachments/assets/a85b674a-10c5-4661-927c-1a82db96c34d)

---

## 🔍 Insights

### \[1] Top Categories by Order Volume

* **Bikes** have the highest number of orders, followed by **Accessories** and **Clothing**.

### \[2] Top Subcategories

* **Road Bikes**, **Tires and Tubes**, and **Mountain Bikes** lead in total order volume.

### \[3] Top Products by Profit

* `Mountain-200 Silver, 46` and `Mountain-200 Black, 38` are the top-performing products based on dynamic profit.

### \[4] Performance Switch

* Users can toggle between **Profit** and **Loss** to dynamically update visuals.

### \[5] Geographical Insights

* Sales are spread across **North America**, **Europe**, and **Australia** with clear regional indicators for performance.

---

## 🗂️ Features Implemented

* **Toggle Switch** for Profit/Loss.
* **Dynamic KPI Table** using DAX.
* **Relationship modeling** with multiple dimension tables.
* **Interactive visuals** with slicers and filters.
* **Geographical analysis** using Map visual.
* **Drill-through** capabilities on products and categories.

---

## 📤 Deployment

* Published to **Google drive link** for wider access.
* Scheduled refresh configured for real-time insights.

---

