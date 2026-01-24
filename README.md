# 🚖 OLA Data Analyst Project

## 📌 Project Overview

This project is an end-to-end **Data Analyst case study** based on a simulated OLA ride-booking dataset.
The objective is to analyze ride behavior, cancellations, revenue, ratings, and operational performance using **SQL and Power BI**.

The project demonstrates **data analysis, querying, KPI calculation, and dashboard building skills** commonly required for entry-level and intermediate Data Analyst roles.

---

## 📊 Dataset Description

* **City:** Bengaluru
* **Time Period:** 1 Month
* **Records:** ~100,000 bookings
* **Data Type:** Synthetic (dummy data created for analysis)

### Key Columns

* Booking_ID
* Booking_Status
* Customer_ID
* Vehicle_Type
* Pickup_Location / Drop_Location
* VTAT / CTAT
* Cancelled Rides (Customer & Driver)
* Incomplete Rides & Reasons
* Booking_Value
* Payment_Method
* Ride_Distance
* Driver_Ratings
* Customer_Rating

---

## 🛠 Tools & Technologies Used

* **SQL (MySQL/PostgreSQL)** – Data querying & analysis
* **Power BI** – Dashboard creation & DAX measures
* **Excel / CSV** – Data storage & preprocessing

---

## 🔍 SQL Analysis Performed

Key business questions answered using SQL:

1. Successful bookings analysis
2. Average ride distance by vehicle type
3. Customer and driver cancellation counts
4. Top 5 customers by number of rides
5. Revenue from completed rides
6. Ratings analysis by vehicle type
7. Payment method usage (UPI, Cash, etc.)
8. Incomplete rides with reasons

SQL **Views** were created for reusable and optimized queries.

---

## 📈 Power BI Dashboard

The Power BI report is divided into the following views:

### 1️⃣ Overall Performance

* Ride Volume Over Time
* Booking Status Breakdown

### 2️⃣ Vehicle Insights

* Top Vehicle Types by Ride Distance

### 3️⃣ Revenue Analysis

* Revenue by Payment Method
* Top 5 Customers by Booking Value
* Ride Distance Distribution

### 4️⃣ Cancellation Analysis

* Customer Cancellation Reasons
* Driver Cancellation Reasons
* **Cancellation Rate (DAX)**

## 📐 Key Metrics (DAX)

* Total Bookings
* Cancelled Bookings
* Cancellation Rate
* Total Revenue
* Average Ratings
* Ride Distance Metrics

---

## 🎯 Business Insights

* Weekend rides show higher demand and revenue
* Customer cancellations are under controlled limits
* Prime and SUV vehicles generate higher booking value
* UPI is the most used payment method
* Ratings correlate strongly with ride completion

---

## ▶️ How to Run the Project

1. Import the dataset into **MySQL / PostgreSQL**
2. Execute SQL scripts or views for analysis
3. Load cleaned data into **Power BI**
4. Create measures using DAX
5. Build and explore dashboards

---

## 📎 Learning Outcome

* Real-world SQL querying
* KPI calculation using DAX
* Business-oriented dashboard design
* Data storytelling for stakeholders

---

## 👤 Author

**Vasudev Narvekar**
Aspiring Data Analyst | Power BI | MySQL | Analytics
