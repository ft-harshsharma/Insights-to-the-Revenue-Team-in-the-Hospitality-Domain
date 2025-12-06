# Insights-to-the-Revenue-Team-in-the-Hospitality-Domain
This dashboard provides a comprehensive performance overview of AtliQ Grands across all hotel properties, highlighting occupancy trends, revenue patterns, and customer behavior.



## 🏨 **Project Overview**

AtliQ Grands owns multiple luxury & business hotels across India.  
Due to poor decision-making and competitor strategy shifts, they lost significant **market share and revenue** in the 5-star segment.

To regain revenue, the company decided to adopt **Business & Data Intelligence**

## 📂 **Dataset Description**

The project contains **5 tables**:

### **1. dim_date**
- Date  
- Month-Year (MMM YY)  
- Week number  
- Day type (Weekend/Weekday)

### **2. dim_hotels**
- Property ID  
- Property Name  
- Category (Luxury / Business)  
- City  

### **3. dim_rooms**
- Room ID  
- Room Class (Standard, Elite, Premium, Presidential)

### **4. fact_aggregated_bookings**
- Property ID  
- Check-in date  
- Room category  
- Successful bookings  
- Capacity  

### **5. fact_bookings**
- Booking ID  
- Booking date  
- Check-in & check-out dates  
- Number of guests  
- Booking platform  
- Ratings  
- Booking status (Cancelled / Checked Out / No Show)  
- Revenue generated  
- Revenue realized  

---

## 📊 **Created Metrics (KPIs)**

### **1. Revenue**
Total earnings generated from room bookings.



### **2. ADR (Average Daily Rate)**
**Formula:**  
ADR = Total Room Revenue / Rooms Sold  
Represents the average price at which rooms are sold.



### **3. RevPAR (Revenue Per Available Room)**
**Formula:**  
RevPAR = ADR × Occupancy %  
Measures revenue efficiency per available room.



### **4. Occupancy %**
**Formula:**  
Occupancy % = Rooms Sold / Total Available Rooms  
Indicates how many rooms were occupied.



### **5. Realisation %**
**Formula:**  
Realisation % = 1 − (Cancellations / Total Bookings)  
Shows the percentage of bookings that convert into stays.



### **6. DSRN (Daily Sellable Room Nights)**
Number of rooms available for sale per day, excluding maintenance/blocked rooms.



### **7. DBRN (Daily Booked Room Nights)**
Total number of room nights booked per day—helps analyze booking volume.



### **8. DURN (Daily Utilized Room Nights)**
Room nights actually utilized (after cancellations and no-shows).  
Directly linked to realized revenue.




---

## 📈 **Dashboard Summary**
**Overall financial performance** — including total revenue, ADR, RevPAR and revenue contribution by cities and room classes.

**Operational efficiency indicators** — such as Occupancy %, Realisation %, room sold trends, cancellations, and booking lead time behavior.

**Room performance metrics** — benchmarking room categories across RevPAR, DSRN, DBRN, and DURN to identify high- and low-performing segments.

**Booking & customer behavior insight**s — including weekday/weekend patterns, booking window analysis, and demand fluctuations.

**Property-level performance comparison** — enabling management to quickly identify hotels under/overperforming relative to company averages.

---

# 🔍 **Observed Data Insights**

## 📊 Key Insights from AtliQ Grands Analysis

### ⭐ 1. Overall Guest Satisfaction
- The **average customer rating is 3.6**, indicating moderate guest satisfaction with clear room for improvement.

### 📉 2. Revenue & Booking Volatility
- Significant **dip in revenue during week 30 and 31**, which directly aligns with declines in:
  - Booking Count  
  - RevPAR  
- The data shows *random fluctuations* where revenue and bookings drop **16–20%**, then recover, then drop again — indicating **unstable demand patterns** or **lack of a steady pricing/demand strategy**.

### 💰 3. No Weekday vs Weekend Pricing Strategy
- **ADR remains the same** across weekdays and weekends.
- This indicates **no dynamic pricing strategy**, resulting in missed revenue opportunities.

### 🏨 4. Business Mix: Luxury Dominant
- Majority of revenue comes from **luxury-category hotels**, suggesting:
  - Strong brand pull in premium segment  
  - But higher risk during downturns due to price sensitivity

### 🚪 5. Room Category Performance
- **Elite rooms generate the highest revenue**, indicating strong customer preference.
- **Presidential rooms show the highest occupancy %** among room categories.

### 🏚️ 6. Low Performing Property: AtliQ Seasons
- Lowest **occupancy %**  
- Lowest **ratings**  
- Represents a high-priority target for operational and quality improvements.

### 🏨 7. Top Performing Property: AtliQ Blu
- Shows **high occupancy** and **high customer ratings**.
- Indicates strong operational performance and customer experience.


### **5. City-Level Performance**
- Bangalore generates highest revenue.
- Delhi shows highest occupancy.

---

# 🧩 **Final Recommendations**

## **1. Dynamic Pricing Engine**
Adjust room pricing based on:
- Day of week  
- Seasonality  
- Occupancy percentage  
- Booking lead time  

## **2. Reduce Cancellations**
- Introduce non-refundable discounted rates  
- Loyalty points for completed stays  

## **3. Improve Operational Efficiency**
- Increase staff during peak weekends  
- Reduce check-in bottlenecks  
- Improve room turnover process  

## **4. Enhance Loyalty & Repeat Business**
- Personalized app/email offers  
- Exclusive upgrades for frequent customers  

## **5. Property Audit Program**
Evaluate:
- Competitor pricing  
- Service quality  
- Room profitability  
- Local market saturation  

---

# 🛠️ **Tech Stack**
- **Power BI**  
- **MS Excel**  
- **DAX**  
- **Data Modeling**  

---

# 📁 **Project Structure**
```
📦 AtliQ-Grands-Analytics
 ┣ 📂 datasets
 ┣ 📂 powerbi-dashboard
 ┣ 📂 images
 ┣ 📜 README.md
 ┗ 📜 insights-summary.pdf
```

---

# 📢 **Conclusion**

This project demonstrates how data-driven intelligence helps AtliQ Grands:
- Regain revenue  
- Improve customer experience  
- Reduce cancellations  
- Optimize operations  
- Compete effectively in luxury hotel segment  

---

If you want, I can now:
- Add metrics list  
- Add business questions  
- Add your insights  
- Add visual placeholders  

Just send them and I’ll integrate them.  
