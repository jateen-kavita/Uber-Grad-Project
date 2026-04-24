🚖 Uber NCR — Ride Fulfillment Efficiency Analysis
Project Overview
An end-to-end business analytics case study on Uber's National Capital Region (NCR) operations, analyzing why nearly 38% of ride bookings fail to convert into completed rides — and what can be done about it.
This project was completed as part of the NextLeap Business Analytics Fellowship (Cohort 5).

Problem Statement
Out of 148,767 total bookings recorded across Uber NCR in 2024, only 92,257 rides were completed — a Ride Completion Rate of 62.01%. The remaining 56,510 failed bookings represent an estimated ₹28.7 million in annual revenue leakage.

Primary Metric: Ride Completion Rate = Completed Rides / Total Bookings → 92,257 / 148,767 = 62.01%


Dataset
AttributeDetailSourceUber NCR Operations DataTime PeriodJanuary 2024 – December 2024GeographyDelhi, Gurgaon, Noida, Faridabad (NCR)Total Rows (Raw)150,000Total Rows (Clean)148,767Columns21 original + 6 helper columnsUnique Pickup Locations176Vehicle Categories7

Tools Used

Microsoft Excel — Data cleaning, pivot tables, helper columns, charts, dashboard
Excel Functions — COUNTIF, COUNTBLANK, TRIM, IFS, TEXT, MIN/MAX, SUMIFS


Key Findings
1. Driver-Side Failures Dominate

Driver-side failures account for 24.99% of all bookings — 3.5x higher than customer-side failures (7.01%)
Cancelled by Driver: 26,779 rides (18%)
No Driver Found: 10,401 rides (6.99%)

2. Geographic Hotspots

Vinobapuri (54.6%) and Akshardham (56.2%) are 7–8% below the NCR average
10 locations consistently underperform, indicating localized supply shortages

3. Problem is Systemic, Not Segment-Specific

Completion rate variance across all 7 vehicle types: only 1.1%
Time of day variance: only 0.7%
The failure pattern is identical across all segments — this is a platform-wide supply problem

4. Driver Behaviour Drives Customer Cancellations Too

55% of customer cancellations are caused by driver behaviour (not moving to pickup, asking customers to cancel, non-functional AC)

5. Revenue Impact
Failure CategoryFailed RidesEst. Revenue LostCancelled by Driver26,779₹13,603,732No Driver Found10,401₹5,283,708Cancelled by Customer10,424₹5,295,392Incomplete Rides8,906₹4,524,248TOTAL56,510₹28,707,080

Recommendations & Expected Impact
ActionPriorityExpected RecoveryLocation-based driver incentives & pre-positioningHigh₹1.5–2.0M / ~3,000–4,000 ridesDriver accountability & quality programHigh₹4.0M / ~8,000 ridesGPS & address validation improvementsMedium₹2.3M / ~4,600 ridesSupply-side driver recruitment & incentivesMedium₹2.6M / ~5,200 rides
Combined impact: ~20,800 rides recovered, completion rate improved to 68–70%, ~₹10M unlocked annually

Files in This Repository
Uber-Grad-Project/
│
├── Dataset/                  # Raw and cleaned dataset (Excel)
├── NL_Uber.pdf               # Full analysis report (PDF)
└── README.md                 # Project documentation

About
Analyst: Jateen Kavita
Program: NextLeap Business Analytics Fellowship — Cohort 5
Focus Area: Operations Analytics | Ride Fulfillment | Revenue Leakage
