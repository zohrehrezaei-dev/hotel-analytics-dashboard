# Hotel Booking Analytics Dashboard

Interactive Power BI dashboard analyzing 119,000+ hotel booking records to uncover customer behavior patterns, cancellation drivers, and revenue optimization opportunities.

## 📊 Project Overview

- **Dataset**: Hotel bookings data (2015-2017)
- **Records Analyzed**: 119,391 bookings
- **Tools**: Python (pandas, numpy), Power BI, Statistical Analysis
- **Focus**: Customer segmentation, cancellation prediction, revenue analysis

## 🎯 Key Insights

- Identified 35.38% cancellation rate with customers from the Online TA market segment
- Discovered top customer segment (Online Travel Agencies (TA)) contributing to 64.6% of revenue
- Found seasonal trends showing summer and spring as peak booking periods
- Analyzed 10 countries representing 93% of total bookings

## 📈 Dashboard Features

![Dashboard Overview](Overview.png)

### Key Metrics Tracked
- Total Revenue & ADR (Average Daily Rate)
- Booking vs Cancellation Rates
- Customer Segmentation Analysis
- Geographic Distribution
- Seasonal Trends

![Key Metrics](Cancellation.png)
![Key Metrics](Geographic.png)
https://github.com/zohrehrezaei-dev/hotel-analytics-dashboard/blob/main/Temporal.PNG
### Analysis Highlights
- Customer segment performance
- Cancellation pattern analysis by lead time
- Revenue trends by hotel type & season
- Market segment effectiveness

## 🛠️ Technical Implementation

### Data Cleaning & Preparation (Python)
- Handled missing values in agent, company, country columns
- Fixed negative ADR values and zero-guest bookings
- Created derived features: total_nights, total_revenue, booking_date
- Categorized lead times and customer segments

### Dashboard Development (Power BI)
- Interactive filters by date, hotel type, country
- DAX measures for revenue calculations and KPIs
- Custom visuals for trend analysis
- Responsive layout optimized for insights delivery


