Hotel Revenue at Risk — Power BI Analytics Project

📊 Project Overview

[PowerBi Dashboard](./Dashboard/Hotel_Analysis(Reject%20Rate_Problem&Solution).pbix)

Hotel Revenue at Risk is an interactive Power BI analytics project focused on understanding, analysing, and reducing hotel booking cancellations.

The project analyses 87,229 hotel bookings across 37 features covering the period July 2015 to August 2017, across City and Resort hotels and multiple customer and market segments.

The objective is to identify the scale and drivers of booking cancellations, determine where revenue is at risk, and translate the findings into actionable revenue-recovery strategies.

![Dash Board](/Images/Intro%20Dashboard%20HA.jpeg)

🎯 Business Problem

Hotels hold large volumes of booking data across hotel types, market segments, distribution channels, customer types, countries, deposit terms and booking behaviours.

The dashboard addresses four key questions:

How large is the cancellation problem?

Who cancels and when?

Why are bookings being cancelled?

How much revenue could potentially be recovered through targeted action?

📁 Dataset

[Dataset](./Dataset/hotel_bookings_clean.csv) (Excel file)

| **Attribute**         | **Details**                      |
| --------------------- | -------------------------------- |
| **Total Bookings**    | 87,229                           |
| **Features**          | 37                               |
| **Arrival Period**    | Jul 2015 – Aug 2017              |
| **Hotel Types**       | City Hotel, Resort Hotel         |
| **Guest Countries**   | 178                              |
| **Customer Segments** | TA/TO, Direct, Corporate, Groups |


 
 ### 🛠️ Analytical Approach


The project followed a four-stage analytics approach:


**1. Prepare – Data Preparation**
Cleaned and structured **87,229 hotel booking records**, engineered lead-time buckets and revenue-related measures, and created a cancellation flag to enable customer and booking-level analysis.

**2. Measure – KPI Development**
Defined key performance indicators to quantify cancellation impact, including **27.5% cancellation rate, 24.0K cancelled bookings, and €11.47M estimated booking value at risk**.

**3. Visualise – Interactive Dashboard**
Developed a multi-page **Power BI dashboard** with interactive slicers for **Deposit Type, Hotel Type, Market Segment, and Customer Type**, enabling deeper analysis of cancellation patterns and risk segments.

**4. Act – Business Recommendations**
Translated insights into actionable revenue-recovery strategies, including **differentiated deposit policies, long-lead booking management, and risk-based occupancy planning**. A **20% reduction in cancellations** was estimated to potentially recover approximately **€2.29M** in booking value.


📈 Dashboard Pages
Page 1 — Hotel Revenue at Risk
![Page 1](/Images/Page%201%20HA.jpeg)

Provides an overview of the dataset, booking scale, hotel types and customer segments.

Page 2 — Overview: Scale of Cancellations
![Page 2](/Images/Page%202%20HA.jpeg)

Highlights the overall cancellation problem and compares cancellation exposure across hotel types.

Page 3 — Who Cancels and When
![Page 3](/Images/Page%203%20HA.jpeg)

### Cancellation Behaviour Analysis

Analysed cancellation patterns across key booking and customer dimensions:

* **Deposit Terms** – Evaluated how deposit type influences cancellation behaviour.
* **Lead Time** – Compared cancellation rates across different booking lead-time periods.
* **Guest Type** – Analysed differences between **repeat and first-time guests**.
* **Market Segment** – Identified cancellation patterns across customer segments.
* **Distribution Channel** – Assessed cancellation behaviour across booking channels such as **Online Travel Agencies (OTAs), Direct, and Corporate**.
* **Guest Geography** – Examined cancellation patterns across **guest countries and regions**.

Page 4 — Why It Happens: Root Causes
![Page 4](/Images/Page%204%20HA.jpeg)

### Cancellation Drivers & Revenue Impact

Analysed the key factors associated with booking cancellations, including:

* **Lead Time** – Examined how cancellation behaviour changes with the time between booking and arrival.
* **ADR** – Evaluated the relationship between room pricing and cancellation patterns.
* **Booking Changes** – Assessed whether modifications to bookings are associated with higher cancellation likelihood.
* **Special Requests** – Analysed whether the number of special requests differs between cancelled and retained bookings.
* **Assigned Room Type** – Examined cancellation patterns across different room types.

### From Insights to Action

Translated the identified cancellation drivers into **practical revenue-management actions**, focusing on reducing high-risk cancellations and estimating the **potential booking value that could be recovered** through targeted interventions.


🔍 Key Insights

Cancellation Exposure

27.52% of bookings were cancelled.

Approximately 24.0K of 87.2K bookings were cancelled.

Estimated booking value at risk was €11.47M.

Hotel-Level Risk

City Hotel: 30.1% cancellation rate

Resort Hotel: 23.5% cancellation rate

Lead-Time Effect

Cancellation risk increased substantially with longer lead times:

8.4% cancellation rate for bookings with 0–7 days lead time

40.8% for bookings with 365+ days lead time

Guest Behaviour

Repeat guests had a 7.7% cancellation rate.

First-time guests had a 28.3% cancellation rate.

Deposit Terms

Non-refundable bookings showed a 94.7% cancellation rate in the analysed dataset.

Distribution Channel

Online Travel Agency (Online TA) bookings represented approximately 81% of revenue at risk, equivalent to €9.29M of €11.47M, with a 35.4% cancellation rate.

💡 Revenue Recovery Strategy

The project proposes four major actions:

Differentiated Deposit Policy
Apply stricter terms or higher deposits to long-lead, high-ADR segments.

Manage Long-Lead, High-Value Bookings
Use targeted reminders and proactive confirmation for early bookings.

Increase Guest Engagement
Encourage special requests and pre-arrival interactions to strengthen booking commitment.

Risk-Based Occupancy Planning
Incorporate cancellation patterns into demand forecasting and inventory planning.

💰 Projected Impact

A scenario was developed assuming a 20% reduction in cancellations.

Under this scenario:

Cancellation rate decreases from 27.52% to 22.02%

Approximately €2.29M in booking revenue could potentially be recovered

Note: The €2.29M figure is a scenario-based estimate from the project analysis, not a guaranteed financial outcome.

📌 Business Value

The dashboard converts raw hotel booking data into a decision-support tool that allows management to:

Monitor cancellation exposure

Identify high-risk customer and booking segments

Diagnose behavioural drivers of cancellations

Quantify booking value at risk

Evaluate potential revenue recovery

Support more informed deposit, occupancy and customer-engagement decisions

🔮 Future Scope

The project identifies three potential next steps:

Predict: Build a model to score cancellation risk at the time of reservation.

Pilot: Test deposit and reminder strategies on high-risk segments.

Monitor: Refresh the dashboard regularly and identify emerging high-risk segments.

🧰 Tools & Skills

Microsoft Power BI

Data Cleaning & Preparation

KPI Development

Interactive Dashboard Design

Business Analytics

Data Visualisation

Revenue & Cancellation Analysis

Business Recommendation & Scenario Analysis


📌 Project Summary

87,229 bookings → 27.52% cancellation rate → €11.47M booking value at risk → ~€2.29M potential recovery under a 20% cancellation-reduction scenario.

This project demonstrates how Power BI can be used to move from data → insight → business action, with a focus on hotel revenue protection and cancellation management.