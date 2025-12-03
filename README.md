📊 Ola Ride Analytics Dashboard – Power BI

A comprehensive Power BI analytics dashboard built to analyze Ola ride data for one month (1st July 2024 – 30th July 2024).
This project showcases expertise in data cleaning, modeling, DAX measures, visualization design, and business insight generation.

🚀 Project Overview

This dashboard provides a 360° view of Ola ride activity, covering total bookings, ride performance, payment analysis, cancellation insights, and customer/driver behavior.
It helps business teams identify operational bottlenecks, revenue opportunities, and customer experience issues.

🎯 Key Features
1️⃣ Ride Volume Analysis

Trend of daily bookings across the month

Total Bookings: 20,407 rides

Booking value: ₹11M

Identifies peak and low-demand days to support operations planning

2️⃣ Booking Status Breakdown

Success Rate: 62%

Canceled Bookings: 28%

Failure reasons visualized (Driver Not Found, Canceled by Driver, etc.)

3️⃣ Payment Mode Insights

Breakdowns for Cash, UPI, Wallet, Cards

Total booking value and volume per payment type

Helps identify customer payment preferences

4️⃣ Top Customer Insights

Ranked by booking value

Example:

CID836942 — ₹3757

CID307511 — ₹3242

Total of top 5: ₹16,278

5️⃣ Cancellation Analysis
Canceled by Customer

Major reasons:

Driver asked to cancel — 26.53%

Change of plans — 19.61%

Wrong address — 9.18%

Canceled by Driver

Top reasons:

Customer-related issue — 29.12%

Personal & car issues — 20.31%

Clear insight into service quality gaps.

6️⃣ Customer & Driver Ratings

Ratings remained stable between 3.98 – 4.02

Identifies service satisfaction trends

🧰 Tools & Technologies Used

Power BI Desktop

Power Query (Data Cleaning & ETL)

DAX (Measures Creation)

Data Modeling (Star Schema)

Excel / CSV (Data Source)

📐 Important DAX Measures (Samples)

Total Bookings = COUNT('Bookings'[Booking ID])

Successful Bookings = CALCULATE([Total Bookings], 'Bookings'[Status] = "Success")

Cancellation Rate = DIVIDE([Canceled Bookings], [Total Bookings])

Total Booking Value = SUM('Bookings'[Booking Value])

📈 Key Business Insights

✔ High cancellation rate (28%) indicates operational inefficiencies
✔ Driver not found and driver cancellations form a major bottleneck
✔ UPI & Cash dominate payment modes
✔ Consistent ratings near 4.0 show overall good customer experience
✔ Top customers contribute a significant portion of revenue

📥 Files Included

Power BI dashboard (.pbix)

PDF export of dashboard

README (this file)

📌 How This Project Adds Value

This project demonstrates my skills in:

Data cleaning & transformation

Building KPI-driven dashboards

Creating actionable insights

Designing professional Power BI reports

Communicating findings for business decisions
