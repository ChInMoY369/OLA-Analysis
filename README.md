
# 🚖 OLA Ride Analysis Dashboard

This repository hosts a comprehensive and interactive **OLA ride analytics dashboard project**, designed to provide valuable insights into ride trends, cancellation reasons, payment patterns, and customer behavior. Built using **Power BI**, **MySQL**, and **Excel**, this dashboard enables data-driven decision-making for ride-hailing platforms.

---

## 📊 Project Overview

The **OLA Ride Analysis Dashboard** is an interactive business intelligence project that provides deep insights into OLA’s ride-hailing operations. It uses historical ride data to uncover trends, performance metrics, customer behavior, and operational bottlenecks.

The dashboard is structured across **five interactive pages** in Power BI, integrating datasets processed through **SQL (MySQL)** and **Excel**. The goal is to empower stakeholders with a visual tool to support **data-driven decisions** regarding operations, revenue, and customer satisfaction.

Key questions addressed by the dashboard include:
- What are the ride volumes over time and by vehicle type?
- What are the most frequent reasons for ride cancellations?
- How are customer and driver ratings distributed?
- What is the revenue contribution by payment method and customer segment?
- Which vehicle types and locations perform best?

---

## 🧠 Key Features & KPIs

Here’s a breakdown of what each dashboard page focuses on, along with the **KPIs** and **insights** covered:

### 1. **Overall Overview**
- ✅ **Total Bookings**
- ✅ **Successful Rides**
- ✅ **Canceled & Incomplete Rides**
- ✅ **Ride Volume Over Time**
- ✅ **Booking Status Breakdown (Success, Cancelled, Incomplete)**

### 2. **Vehicle Type Analysis**
- 🚗 **Top Performing Vehicle Types** (by distance and bookings)
- 📏 **Average Ride Distance by Vehicle Type**
- 🌐 **Vehicle-wise Popular Locations (Pickup/Drop Zones)**

### 3. **Revenue Insights**
- 💰 **Total Booking Value**
- 💳 **Revenue by Payment Method (UPI, Cash, Cards)**
- 🧑‍💼 **Top 5 Customers by Booking Value**
- 📈 **Daily Revenue Trends**

### 4. **Cancellations**
- ❌ **Total Cancellations by Customers and Drivers**
- 🔍 **Reasons for Cancellation (e.g., personal issues, vehicle problems, change of plans)**
- 🧾 **Cancellation Ratio by Vehicle Type and Time Period**

### 5. **Ratings**
- ⭐ **Average Customer Rating**
- 🚘 **Average Driver Rating**
- 📊 **Ratings by Vehicle Type**
- 🔁 **Customer vs Driver Ratings Comparison**
- 🧪 **Outlier Detection in Ratings**

---

## 🛠️ Technologies Used

- **Power BI** – For interactive data visualizations and dashboard creation
- **MySQL** – For structured data querying and transformation
- **Excel** – For preprocessing, formatting, and supplementary calculations

---

## 🗂️ Files Included

- `Dataset.csv` / `Dataset(Excel).xlsx` – Raw data for the dashboard
- `OLA Analysis.pbix` – Power BI dashboard file
- `Ola_Analysis_Queries.sql` – SQL queries for MySQL analysis
- `Preview Folder` – This folder contains a preview of the dashboard

---

## 🚀 Getting Started

### Step 1: Set Up the Database
- Import the schema and data into your MySQL instance using `Ola_Analysis_Queries.sql`.

### Step 2: Open the Dashboard
- Open the `OLA Analysis.pbix` file in Power BI Desktop.
- Update data source settings to point to your local MySQL and Excel files if needed.

### Step 3: Explore
- Navigate through the dashboard pages to explore trends, insights, and KPIs.

---

## 📷 Preview

<p align="center">
  <img src="Preview/overview.png" width="150"/>
  <img src="Preview/vehicle_type.png" width="150"/>
  <img src="Preview/revenue.png" width="150"/>
  <img src="Preview/cancellations.png" width="150"/>
  <img src="Preview/ratings.png" width="150"/>
</p>

---

## 🤝 Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request if you'd like to add new features or suggest improvements.

---

## 📄 License

This project is licensed under the MIT License.

---

## 💬 Feedback

Feel free to explore the repository and use the dashboard for your own ride data analysis projects.  
For questions or suggestions, contact me at **ctalukdar34@gmail.com** or connect on [LinkedIn](https://www.linkedin.com/in/chinmoy-talukdar-5a32b9329/).
