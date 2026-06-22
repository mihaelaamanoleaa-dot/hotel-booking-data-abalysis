Dataset Contents
This repository contains the following datasets generated during the analysis:

`hotel_bookings.csv`: The original, raw dataset containing reservation details for both a City Hotel and a Resort Hotel.
`cleaned_bookings.csv`: The processed dataset where missing values were handled and new structured columns (like Month Number) were engineered for easier time-series analysis.
`ADR Seasonality.csv`: An aggregated view tracking the Average Daily Rate (ADR) across different months, highlighting pricing peaks and low seasons for both hotel types.
`AVG lead vs canceled.csv`: An analysis grouping the 'lead time' (days between booking and arrival) to demonstrate its correlation with the likelihood of a cancellation.
`Cancellation Risk.csv`: A pivot summary that evaluates cancellation rates across different market segments and deposit types (e.g., No Deposit vs. Non Refund), identifying which booking channels carry the highest risk of no-shows.

1. The Revenue Seasonality Bar Chart
Discovering When the Hotels Make the Most Money (Seasonality Analysis)
  I wanted to find out which months generate the most revenue so the business can plan its marketing budget effectively. I analyzed the Average Daily Rate (ADR) across the entire year for both City and Resort hotels.
Data Shows: City Hotels have very steady, consistent pricing all year round.
Resort Hotels experience a massive spike in pricing power during July and August, but drop significantly in the winter.
My Business Recommendation: The marketing team should run aggressive ad campaigns for the Resort Hotel in the spring to lock in those highly profitable summer bookings before competitors do. For the City Hotel, marketing can be kept at a steady, year-round pace.

2. The Lead Time Risk Line Chart
Finding the Root Cause of Cancellations (Lead Time Analysis)
  Cancellations cost the hotel money. I used a '5 Whys' critical thinking approach to figure out the root cause behind why customers cancel. I suspected it had to do with how far in advance they booked (Lead Time).
Data Shows: The line chart reveals a very clear upward trend. The further in advance a customer makes a reservation, the more likely they are to cancel it. For example, customers who book 6+ months in advance have a much higher cancellation rate than spontaneous travelers.
My Business Recommendation: To prevent these long-term bookings from turning into cancellations, the hotel should set up an automated email sequence. Sending a friendly reminder or a special upgrade offer a month before their stay can help secure their commitment.

3. The Cancellation Risk Matrix Grouped Bar Chart
Protecting Revenue with Smarter Deposit Policies
  After looking at overall customer behavior, I wanted to find out if specific types of bookings were riskier than others. I built a matrix to compare where the booking came from (Market Segment) against how they paid (Deposit Type).
Data Shows:The data highlighted one major problem area: "Online Travel Agents" (Online TAs). When these agents are allowed to book a room with a "No Deposit" policy, nearly 35% of them cancel. However, when a "Non Refund" policy is applied to that exact same group, cancellations drop drastically.
My Business Recommendation: The hotel needs to update its rules for Online Travel Agents. By requiring a non-refundable deposit for OTA bookings, the hotel will immediately reduce its churn rate and stop holding empty rooms that could be sold to paying guests.
