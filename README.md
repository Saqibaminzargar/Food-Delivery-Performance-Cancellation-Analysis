# Food Delivery Performance & Cancellation Analysis

An end-to-end data analytics project analyzing food delivery order performance and cancellations across major Indian cities built using **Python** for data generation and cleaning, **SQL** for querying and analysis, and **Power BI** for interactive dashboard reporting. The project identifies when, where, and why orders get cancelled, and how that connects to revenue and customer satisfaction.

---

## Project Overview

Cancellations quietly drain revenue and customer trust in the food delivery business. This project analyzes **5,000+ food delivery orders** across 7 major Indian cities, combining revenue performance metrics with cancellation patterns to uncover operational bottlenecks and improve customer experience.

The dashboard is built across **2 interactive pages**  a revenue & sales performance overview and a detailed cancellation analysis.

---

## Business Problem

The company wants to understand:
- When and why cancellations happen
- Which cities and time periods are most affected
- How delivery time and payment method relate to cancellations
- Which restaurants and cities drive the most revenue
- Where operational improvements would have the biggest financial impact

---

## Data Source

- **Dataset:** Synthetic data generated using AI, simulating realistic food delivery order patterns
- **Records:** ~5,000 orders
- **Coverage:** 7 major Indian cities — Hyderabad, Pune, Delhi, Bengaluru, Chennai, Mumbai, Kolkata

---

## Key KPIs

| Metric | Value |
|---|---|
| Total Orders | 5K |
| Delivered Orders | 3,965 |
| Cancellation Rate | 20.70% |
| Total Revenue | 6.55M |
| Avg Order Value | 1.31K |
| Avg Delivery Time | 51.92 min |
| Avg Customer Rating | 2.97 |

---

## Dashboard Pages

### 1. Revenue & Sales Performance
Revenue by city, top restaurants by revenue, revenue by payment method, and monthly revenue/cancellation trend with a city filter for drill-down.

### 2. Cancellation Analysis
Orders vs. cancellations by hour, average delivery time by peak hour, cancellations by age category, city, payment method, and customer rating.

---

##  Key Insights

- Delivery operations stay fairly stable throughout the day, but morning orders take slightly longer to deliver
- Peak order hours align with the highest cancellation spikes — restaurants and delivery partners appear to struggle with demand surges during these windows
- **Hyderabad and Pune** are top priorities for operational improvement, since reducing cancellations here would have the greatest financial impact
- **Adults** account for the majority of cancellations (63.96%), compared to Young (18.36%) and Senior (17.68%) customers
- A clear link exists between higher cancellation rates and lower customer satisfaction **Pune** in particular could boost ratings by improving service quality
- **Hyderabad, Pune, and Delhi** lead in revenue generation, making them key markets to protect and grow
- Cash and Card payments show higher cancellation shares (30.72% / 32.85%) compared to UPI (36.43%)

---

## Tools & Techniques Used

- **Python** — data cleaning, and preprocessing (Pandas, NumPy)
- **SQL** — data querying, aggregation, and analysis
- **Power BI** — DAX measures, interactive report design
- **Power Query** — data transformation and loading
- **DAX** — calculated KPIs (Cancellation Rate, Avg Delivery Time, Avg Order Value)
- **Data Visualization** — combo charts, donut charts, bar charts, KPI cards

---

## Business Impact & Recommendations

- Strengthen restaurant and delivery partner capacity during **peak order hours** to reduce demand driven cancellations
- Prioritize operational fixes in **Hyderabad and Pune**, where cancellation reduction would have the largest revenue impact
- Investigate service quality issues in **Pune** to improve customer ratings alongside cancellation rates
- Use age-based cancellation patterns to tailor communication and retention strategies for **Adult** customers, the largest cancellation group

---

🔗 [LinkedIn](https://linkedin.com/in/saqib-amin-31b1ba2a1/) 
