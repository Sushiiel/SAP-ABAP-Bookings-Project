# 📊 SAP ABAP Bookings Project

This project demonstrates **end-to-end ABAP development** using a custom table `ZBOOKINGS`.  
It covers **table creation, data insertion, ALV reports, analytics, and risk scoring**.  
Ideal for showcasing ABAP skills (Open SQL, LOOPs, CASE, SALV ALV, custom logic).  

---

## 🚀 Project Structure

### 1. `ZBOOKINGS_DEMO`
- Inserts **200 demo rows** into the custom table `ZBOOKINGS`.
- Data includes:
  - Booking ID
  - Customer ID
  - Flight Date
  - Price
  - PaymentSum

✅ Used for **test dataset generation**.

**Screenshot:**  
![ZBOOKINGS_DEMO](images/zbookings_demo.png)

---

### 2. `ZBOOKINGS_REPORT`
- ALV **Risk Scoring Dashboard**.  
- Assigns risk levels based on:
  - **High Value Orders** → High Risk
  - **Delayed Deliveries** → Medium Risk
  - Others → Low Risk
- Displays results in **SALV ALV with headers**.

✅ Demonstrates **risk classification & ALV reports**.

**Screenshot:**  
![ZBOOKINGS_REPORT](images/zbookings_report.png)

---

### 3. `ZBOOKINGS_ANALYTICS`
- Analytics program with **radio buttons** to choose reports:
  1. **Monthly Statistics** → Total revenue & bookings grouped by month.
  2. **Top Customers** → Revenue contribution per customer.
  3. **Top Bookings** → Highest value bookings by PaymentSum.

✅ Demonstrates **aggregations, SQL + LOOP logic, SALV ALV display**.

**Screenshot:**  
![ZBOOKINGS_ANALYTICS](images/zbookings_analytics.png)

---

## 🛠️ Technical Concepts Covered
- **Custom Table Creation** (`ZBOOKINGS`)
- **Mass Data Insertion** (`INSERT`)
- **Open SQL SELECT / DELETE / MODIFY**
- **Control Structures** (LOOP, IF, CASE)
- **SALV ALV Reports**
- **Risk Classification Logic**
- **Aggregations & Analytics (Monthly, Customer, Booking-level)**

---

## 📂 Repository Layout
