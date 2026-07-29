# 🚖 Uber Ride Sharing Analysis Dashboard

## 📊 Project Overview
This project analyzes ride-sharing operations using Power BI to uncover insights related to booking performance, cancellations, customer behavior, and operational efficiency.

The dashboard focuses on identifying patterns in ride completion, cancellation trends, peak demand hours, and service performance across different dimensions.


## 🎯 Objectives
- Analyze ride booking funnel (Total → Completed → Cancelled → Incomplete)
- Identify key factors affecting cancellations
- Understand customer and driver behavior
- Evaluate performance across vehicle types and payment methods
- Detect peak booking hours and operational patterns



## 📁 Dataset
- Source: Kaggle  
- Dataset Link: *(https://www.kaggle.com/datasets/yashdevladdha/uber-ride-analytics-dashboard)*  



## 🧱 Data Description
The dataset contains ride-level information including:

- Booking details (ID, status, time, date)
- Customer and driver interactions
- Cancellation indicators (Customer & Driver)
- Cancellation reasons
- Ratings (Customer & Driver)
- Payment methods
- Operational metrics (CTAT, VTAT)
- Location data (Pickup & Drop)



## 📊 Dashboard Pages

### 🔹 1. Executive Overview
- KPI Metrics:
  - *Total Bookings* - 149K
  - *Total Revenue* - 42M
  - *Completion %* - 62.01%
  - *Cancellation %* - 25%
  - *Incomplete %* - 6%
- Funnel Analysis (Booking Lifecycle)
- Monthly Booking Trend
- Revenue Trend
- Peak Booking Hours Heatmap
## 🔻 Funnel Analysis

The ride booking lifecycle was analyzed using a funnel approach to track the progression from booking to completion and identify drop-offs.

- Total bookings form the top of the funnel, representing overall demand.
- Approximately **62% of bookings are successfully completed**, indicating moderate operational efficiency.
- Around **25% of bookings are cancelled**, highlighting a significant drop-off that impacts revenue and service reliability.
- A smaller portion (~6%) consists of **incomplete rides**, suggesting operational or system-level disruptions.
- The funnel structure helps identify **key loss points**, enabling targeted improvements in cancellation reduction and service fulfillment.

### 🔹 2. Cancellation Analysis
- Customer vs Driver Cancellation Comparison
- Cancellation by Hour
- Cancellation by Pickup Location
- Customer Cancellation Reasons
- Driver Cancellation Reasons



### 🔹 3. Customer & Driver Analysis
- Vehicle Type Performance
- Average Customer & Driver Ratings
- Avg CTAT vs VTAT Trends
- Payment Method Distribution



### 🔹 4. Key Insights
- Completion rate ~62% indicates moderate efficiency
- Cancellation rate (~25%) is relatively high
- Peak bookings occur during evening hours
- Customer cancellations are slightly higher than driver cancellations
- Higher cancellations observed during late hours
- Certain locations show higher cancellation concentration
- Ratings are consistent (~4+) across vehicle types
- UPI is the most preferred payment method



## 🛠️ Tools & Technologies
- Power BI (Data Visualization)
- Excel (Preparation)
- DAX (Measures & Calculations)
- Python (Data Cleaning)



## 📷 Dashboard Preview
<img width="1203" height="678" alt="Overview" src="https://github.com/user-attachments/assets/9e0bd27b-07c9-4391-99ea-e04697f659b0" />
<img width="1202" height="677" alt="Cancellation analysis" src="https://github.com/user-attachments/assets/8912d5df-950f-4ba0-9fef-c56fe9159091" />
<img width="1197" height="677" alt="Customer and Driver Analysis" src="https://github.com/user-attachments/assets/fa0edd47-0e23-4e3f-b744-aa132edc99db" />
<img width="1212" height="683" alt="Insights" src="https://github.com/user-attachments/assets/7564d200-646c-4164-ba14-a0cb87419d5f" />



## 📈 Key Learnings
- Built end-to-end interactive dashboard
- Performed funnel analysis for ride lifecycle
- Applied data cleaning and transformation techniques
- Derived insights using pattern-based analysis
- Improved storytelling using dashboard design


