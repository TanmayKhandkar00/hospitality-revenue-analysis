# Atliq Hospitality Revenue Analysis
This project is part of the Codebasics resume challenge. </br>
Link to the [Challenge](https://codebasics.io/challenge/codebasics-resume-project-challenge/4)
## Overview
AtliQ Grands owns multiple five-star hotels across India. They have been in the hospitality industry for the past 20 years. Due to strategic moves from other competitors and ineffective decision-making in management, AtliQ Grands are losing its market share and revenue in the luxury/business hotels category. As a strategic move, the managing director of AtliQ Grands wanted to incorporate “Business and Data Intelligence” to regain their market share and revenue. However, they do not have an in-house data analytics team to provide them with these insights.

Their revenue management team had decided to hire a 3rd party service provider to provide them with insights from their historical data.

## Data Model
![Data Model](/Resources/data_model.png)
## Dashboard
![](/Resources/Dashboard.png)
### **KPIs**
The dashboard highlights the following **KPIs** at the top-left, each displaying the week-on-week change:
  1. **Revenue** - ₹1.69B
  - Total revenue realized across all AtliQ Grands properties.
  2. **RevPAR (Revenue Per Available Room)** - 7.34K
  - RevPAR represents the revenue generated per available room, whether or not they are occupied.
  - RevPAR helps hotels measure their revenue generating performance to accurately price rooms and can help hotels measure themselves against other properties or brands.
  3. **DSRN(Daily Sellable Room Nights)** - 2.53K
  - DSRN (Daily Sellable Room Nights) represents the average number of rooms available for sale per day over a given time period.
  - It helps measure the total room capacity that a hotel or group of hotels can offer to guests daily.
  4. **Occupancy %** - 57.79%
  - Occupancy Percentage (%) measures the proportion of available rooms that were successfully booked and utilized by guests.
  - It is a key performance indicator in the hospitality industry that helps assess hotel efficiency.
  5. **ADR(Average Daily Rate)** - 12.70K
  - ADR is the ratio of revenue to the total rooms booked/sold.
  - It is the measure of the average paid for rooms sold in a given time period.
  6. **Realisation %** -
  - Realisation Percentage (%) measures the proportion of total bookings that successfully resulted in guests checking out.
  - It helps assess how many of the booked rooms were actually utilized by customers.
### Visualizations
1. **Weekend vs Weekday Performance**:
- This table provides a comparative analysis of key hospitality metrics (RevPAR, Occupancy %, ADR, and Realisation %) based on the type of day (Weekday vs Weekend).
- **Higher RevPAR and Occupancy % on weekends** suggest stronger demand for leisure travel.
- ADR is relatively stable across both segments.
- **Recommendation**:
    - Introduce **weekday promotions** to attract more corporate travelers.
    - Adjust **pricing strategies** to optimize revenue based on demand patterns.
2. **Percentage Revenue by Category**:
- A **donut chart** displaying revenue contribution by hotel category: **Luxury (61.62%) vs. Business (38.38%)**.
- The **Luxury segment generates more revenue**, but the Business category still holds a significant share.
- **Recommendation**:
    - Invest in **premium services and packages** to further boost Luxury hotel revenue.
    - Expand marketing efforts for Business hotels to capture more corporate bookings. 
3. **Trends By Key Metrics**: 
- A **weekly trend analysis** of **RevPAR, ADR, and Occupancy %** over multiple weeks.
- **Fluctuations in RevPAR and Occupancy %** indicate seasonal variations or shifts in market demand.
- **ADR** remains constant suggesting consistent pricing over multiple weeks.
- **Recommendation**:
    - Implement **dynamic pricing models** based on peak and off-peak trends.
    - Align marketing campaigns with periods of higher demand.
4. **RevPAR By City**: 
- A **bar chart** comparing RevPAR across cities (Mumbai, Delhi, Bangalore, Hyderabad).
- Mumbai leads in RevPAR, followed by Delhi and Bangalore.  
- Hyderabad has the lowest RevPAR, indicating weaker demand or lower pricing.
- **Recommendation**:
    - **Analyze market conditions in Hyderabad** to understand the lower performance.
    - Increase **advertising and local promotions** to attract guests.
5. **Capacitty, Bookings and Cancellation by Room Type**: 
- A **bar chart** depicting total capacity, bookings, and cancellations for different room types (Elite, Standard, Premium, Presidential).
- The **Elite category has the highest capacity and bookings**, but also significant cancellations.  
- Presidential rooms have the lowest booking volume.
- **Recommendation**:
    - Reduce overbooking risks by **offering better cancellation policies**.  
    - Consider **discounted packages** for underutilized room types.
6. **Realisation percentage and ADR by Platform**:
- A **comparison of Realisation % and ADR across different booking platforms** (LogTrip, Journey, Direct Online, etc.).
- Some platforms have a **lower Realisation %**, indicating high cancellations or no-shows.  
- ADR remains fairly consistent across platforms.
- **Recommendation:**  
  - Strengthen **relationships with high-performing platforms**.  
  - Improve direct booking incentives to reduce dependency on third-party platforms.
7. **Property By Key Metrics Table**: 
- A **detailed table** displaying **Revenue, RevPAR, Occupancy %, ADR, Realisation %, and Cancellations** for each property.
- **Mumbai properties contribute the highest revenue**, with **AtliQ Exotica (Mumbai) leading at ₹117M**, followed by **AtliQ Palace (Mumbai) at ₹100M**.  
- **AtliQ City (Mumbai) has the highest occupancy rate (66.52%)**, indicating strong demand.  
- **AtliQ Seasons (Mumbai) has the lowest occupancy (44.57%)**, signaling potential issues in demand or pricing.  
- **AtliQ Grands (Delhi) has the highest ADR (₹12,696)**, yet its revenue is relatively low at ₹36M, suggesting fewer bookings.  
- **Cancellation rates are fairly consistent across properties (~24-25%)**, implying no location-specific impact.
- **Recommendations:**  
  - **Analyze and replicate success strategies** from high-revenue, high-occupancy properties like AtliQ Exotica and AtliQ Palace.  
  - **Address low occupancy** at AtliQ Seasons (Mumbai) through targeted promotions, better pricing, or enhanced offerings.  
  - **Optimize pricing strategies** for high-ADR but low-revenue properties like AtliQ Grands (Delhi) to boost bookings.

## Key Takeaways & Recommendations
**1. Pricing Optimization**
- Adjust **weekday pricing** to attract business travelers.
- Implement **dynamic pricing** based on seasonal demand trends.

**2. Improve Booking Efficiency**
- Offer **discounts on direct bookings** to improve Realisation %.
- Strengthen partnerships with **high-performing booking platforms**.

**3. Property-Level Enhancements**  
- **Improve occupancy rates** in weaker-performing properties through promotions.  
- Analyze **city-level RevPAR differences** to refine regional strategies.  

**4. Room Type Management**  
- Adjust **inventory and pricing for underperforming room types**.  
- Introduce **special packages** to boost bookings for high-cancellation room types.

## **Final Thoughts**  
This dashboard provides **valuable insights into revenue trends, booking performance, and occupancy rates** across AtliQ Grands properties. By leveraging these insights, the management team can make **data-driven decisions to optimize operations, enhance guest experience, and maximize revenue growth.** 
     

    
