# 🚖 Ola Ride Analytics – Power BI Dashboard

A complete end-to-end Power BI project analyzing Ola ride activity for July 2024.  
This dashboard uncovers trends in bookings, cancellations, payment patterns, top customers, and service quality.

## 📊 Key Highlights
- **20,407 total bookings**
- **₹11M total booking value**
- **62% success rate**
- **28% cancellation rate**
- Deep-dive into *customer cancellations*, *driver cancellations*, *payment modes*, and *ratings*.

## 🚀 Project Objectives
- Analyze ride performance and demand trends.
- Identify major reasons for ride cancellations.
- Study customer and driver behavior through ratings.
- Provide actionable business insights.

## 🛠 Tools Used
- **Power BI Desktop**
- **Power Query**
- **DAX**
- **Excel / CSV**
- **Data Modeling (Star Schema)**

## 📁 Repository Structure
```
📦 ola-ride-analytics-powerbi
│── README.md
│── data/
│── reports/
│── visuals/
│── dax-measures/
│── documentation/
│── licenses/
```

## 📈 Screenshots
Screenshots available inside `/visuals/screenshots/`.

## 🧠 Insights Summary
- High cancellation rate due to *driver not found* and *driver asking to cancel*.
- UPI and Cash dominate payments.
- Customer and driver ratings remain stable (3.98–4.02).

## 🧩 DAX Samples
```DAX
Total Bookings = COUNT('Bookings'[BookingID])

Total Booking Value = SUM('Bookings'[BookingValue])

Success Bookings = CALCULATE([Total Bookings], 'Bookings'[Status] = "Success")

Canceled Bookings = CALCULATE([Total Bookings], 'Bookings'[Status] = "Canceled")

Cancellation Rate = DIVIDE([Canceled Bookings], [Total Bookings])
```
# 📊 Business Insights

## 1️⃣ Ride Volume Analysis
- Total bookings: **20,407**
- Highest traffic days: Mid-month and weekends.
- Shows strong weekday consistency with mild dips on Mondays.

## 2️⃣ Cancellation Insights
### 🔹 Canceled by Customer
Top reasons:
- Driver asked to cancel — **26.53%**
- Change of plans — **19.61%**
- Wrong address — **9.18%**

### 🔹 Canceled by Driver
Top reasons:
- Customer-related issues — **29.12%**
- Personal & car issues — **20.31%**

📌 *Insight:* Both sides contribute heavily to cancellations; operational SOP improvements required.

## 3️⃣ Payment Mode Insights
- UPI and Cash contribute highest ride value.
- Wallet & Card usage low → opportunity for promotions.

## 4️⃣ Customer & Driver Ratings
- Ratings remain between **3.98–4.02**
- Indicates overall stable satisfaction.

## 5️⃣ Top Customers Analysis
Top customers contribute **₹16,278**, showing that repeat premium customers add significant revenue.

## 📌 Final Recommendation Summary
- Improve driver availability to reduce “Driver Not Found.”
- Encourage digital payments with cashback.
- Provide location accuracy nudges to reduce wrong-address cancellations.

## 📬 Contact
For more projects: *Gaurav Pandwar*  
