# Hotel_Booking_EDA
Hotel Bookings Exploratory Data Analysis Using Python

## Project Summary -
Almabetter Hotel Booking EDA Project Using Python.
Hotel booking analysis with AlmaBetter EDA This project relates to hotel reservations and includes a variety of city hotels and resort hotels. There are 32 columns and a total of 119390 rows in this dataset. Data collection, data cleansing and manipulation, and EDA (experimental Data Analysis) are the three categories into which the workflow for data manipulation is divided. The names of some of the columns, including hotel, is_canceled, lead_time, arrival_date_year, arrival_date_month, arrival_date_week_number, arrival_date_day_of_month, and stays_in_weekend_nights, have been updated as the data collection process has progressed. This is done by coding Head(), Tail(), info(), describe(), columns(), and other methods used for data collection. As we proceed, we Identify the distinct value for each column, create a list in tabular format, and also verify the dataset type for each column. Identify some columns with inaccurate data types and fix them afterward. As we discover duplicate items totaling 87396, which are later discarded from the dataset, duplicate data items must also be removed during the data cleaning phase.
We must first perform data manipulation before visualizing any data from the data source. To do that, we examined each columri's null value. After checking, drop the column using the 'drop' method if we find one that has a greater percentage of null values. We are so removed from the "company" column. When there are only a few null values, we fill those null values with the necessary values using the formula.fill()
To achieve greater understanding and business goals, many charts are utilized for data visualization.


## Variables Description

The columns and the data it represents are listed below:
hotel: Name of the hotel (Resort Hotel or City Hotel)
is canceled: If the booking was canceled (1) or not (0)
lead time: Number of days before the actual arrival of the guests
arrival date year: Year of arrival date
arrival date month: Month of month arrival date
arrival date_week number: Week number of year for arrival date
arrival date day_of_month: Day of arrival date
stays in weekend_nights: Number of weekend nights (Saturday or Sunday) spent at the hotel by the guests.
stays in week nights: Number of weeknights (Monday to Friday) spent at the hotel by the guests.
adults: Number of adults among guests
children: Number of children among guests
babies: Number of bables among quests
meal: Type of meal booked
country: Country of guests
market segment: Designation of market segment
distribution_channel: Name of booking distribution channel
is repeated_guest: If the booking was from a repeated guest (1) or not (0)
previous cancellations: Number of previous bookings that were cancelled try the customer prior to the current booking.
previous bookings_not canceled: Number of previous bookings not cancelled by the customer prior to the current booking
reserved room type: Code of room type reserved
assigned roon_type: Code of room type assigned
booking changes: Number of changes/amendments made to the booking
deposit type: Type of the deposit made by the guest
agent: ID of travel agent who made the booking
company: ID of the company that made the booking
daya in waiting list: Number of days the booking was in the waiting list
customer type: Type of customer, assuming one of four categories
adr: Average Daily Rate, as defined by dividing the sum of all lodging transactions by the total number of staying nights
required car parking spaces: Number of car parking spaces required try the customer
total of special_requests: Number of special requests made by the customer
reservation_status: Reservation status (Canceled, Check Out or No-Show)
reservation_status_date: Date at which the last reservation status was updated.
