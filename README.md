# hotel-booking-cancellations-eda (guided by Ayushi Mishra - Tech Classes)
This project is aimed at analyzing patterns of cancellations for City and Resort Hotels and to find relevant solutions to this problem. 

The dataset used for analysis has been obtained from Kaggle and it contains the booking information of two hotels. One of the hotels is a resort hotel (34%) and the other is a city hotel (66%). Let's now have a look at the columns of this dataset.
- 'hotel':- Either city or resort hotel.
- 'is_canceled':- Value indicating if the booking was canceled (1) or not (0).
- 'lead_time':- Number of days that elapsed between the entering date of the booking into the PMS and the arrival date.
- 'arrival_date_year':- Year of arrival date.
- 'arrival_date_month':- Month of arrival date with 12 categories: “January” to “December”
- 'arrival_date_week':- Week number of the arrival date.
- 'arrival_date_day':- Day of the month of the arrival date.
- 'stays_in_weekend_nights':- Number of weekend nights (Saturday or Sunday) the guest stayed or booked to stay at the hotel.
- 'stays_in_week_nights':- Number of week nights (Monday to Friday) the guest stayed or booked to stay at the hotel BO and BL/Calculated by counting.
- 'adults':- Number of adults
- 'children':- Number of children
- 'babies':- Number of babies
- 'meal':- Meal (BB:- Bread & Breakfast)
- 'country':- Country of origin
- 'market_segment':- Market segment designation. In categories, the term “TA” means “Travel Agents” and “TO” means “Tour Operators”
- 'distribution_channels':- Booking distribution channel. The term “TA” means “Travel Agents” and “TO” means “Tour Operators”.
- 'is_repeated_guest':- Value indicating if the booking name was from a repeated guest (1) or not (0)
- 'previous_cancellations':- Number of previous bookings that were cancelled by the customer prior to the current booking
- 'previous_bookings':- Number of previous bookings not cancelled by the customer prior to the current booking
- 'reserved_room_type':- Code of room type reserved. Code is presented instead of designation for anonymity reasons.
- 'assigned_room_type':- Code for the type of room assigned to the booking. Sometimes the assigned room type differs from the reserved room type
- 'booking_changes':- Number of changes/amendments made to the booking from the moment the booking was entered on the PMS.
- 'deposit_type':- No Deposit – no deposit was made; Non Refund – a deposit was made in the value of the total stay cost
- 'agent':- ID of the travel agency that made the booking
- 'company':- ID of the company/entity that made the booking or responsible for paying the booking
- 'days_in_waiting_list':- Number of days the booking was in the waiting list before it was confirmed to the customer
- 'customer_type':- Group – when the booking is associated to a group; Transient – when the booking is not part of a group or contract, and is not associated to other transient booking; Transient-party – when the booking is transient, but is associated to at least other transient booking
- 'adr':- Average Daily Rate (Calculated by dividing the sum of all lodging transactions by the total number of staying nights). The average daily rate (ADR) is a metric widely used in the hospitality industry to indicate the average revenue earned for an occupied room on a given day.
- 'required_car_parking_spaces':- Number of car parking spaces required by the customer
- 'total_of_special_requests':- Number of special requests made by the customer (e.g. twin bed or high floor)
- 'reservation_status':- Check-Out – customer has checked in but already departed; No-Show – customer did not check-in and did inform the hotel of the reason why
- 'reservation_status_date':- Date at which the last status was set. This variable can be used in conjunction with the ReservationStatus to understand when was the booking canceled or when did the customer checked-out of the hotel
- 'name':- Name of the Guest (Not Real)
- 'email':- Email (Not Real)
- 'phone-number':- Phone number (not real)
- 'credit_card':- Credit Card Number (not Real)
