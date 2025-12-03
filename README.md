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

## 📬 Contact
For more projects: *Your Name* | Data Analyst Portfolio  
