#  Hotel Business Performance Dashboard (Power BI Project)

## 1.  Background and Overview

This Power BI dashboard project is designed to analyze the business performance of a fictional hotel chain operating across major Indian metropolitan cities. The objective is to deliver actionable insights into hotel revenue, customer behavior, room occupancy, and booking channels.

It helps hotel management:
- Identify underperforming properties
- Optimize cancellation and refund policies
- Target promotions in off-season periods
- Improve channel-wise booking strategies

---

## 2.  Data Structure and Overview

The dataset follows a star schema with ~30,000 records and consists of:

###  `dimHotel`
- Hotel ID, Hotel Name, City, State, Star Rating

###  `dimCustomer`
- Customer ID, Name, Gender, Country, Booking Preferences

###  `dimDate`
- Date Key, Day, Month, Quarter, Year, Weekend/Weekday Flags

###  `factBookings`
- Booking ID, Hotel ID, Customer ID, Room Type, Booking Channel, Check-In, Check-Out, Nights, Guests, Cancellation Flag, Booking Revenue

###  `factRevenue`
- Revenue ID, Hotel ID, Date Key, Revenue Amount, Refund Amount, Net Revenue

---

## 3.  Executive Summary

This dashboard provides a high-level overview of hotel business health across Indian metro cities. It analyzes revenue generation, booking trends, cancellation behavior, and room type performance to support better hotel management decisions.

Key use cases:
- Monitor revenue and profitability across locations
- Track seasonal occupancy fluctuations
- Identify cancellation-heavy channels
- Align room pricing with customer demand

---

## 4.  Insights Deep Dive

-  **Mumbai and Delhi** generate the highest revenue but also see **high cancellation rates** through OTA channels.
-  **July to September** is consistently low-performing across all cities in terms of bookings and occupancy.
-  **Deluxe rooms** are most booked but have **lower occupancy rates** compared to standard rooms.
-  **Free-cancellation bookings** are 25% more likely to be refunded — often for short-stay customers.
-  Customers booking through **Direct or Corporate channels** have the lowest cancellation and highest retention.

---

## 5.  Recommendations

-  **Encourage rebooking over refunds** by offering credit or discounts for canceled OTA bookings.
-  **Promote offers during off-peak months** using email and loyalty programs to stabilize occupancy.
-  **Focus marketing spend on Direct and Corporate channels** to improve retention and profit margins.
-  Monitor deluxe room pricing and optimize inventory to reduce underutilization.

---

##  Tools Used

- Power BI Desktop
- Excel (for data cleanup)
- DAX, Power Query
- Custom tooltips, drillthrough, and slicers

---

## 👤 Author

> **[Girish K S]**  
> Connect with me on [girishhemanth823@gmail.com]
