# Hotel Booking Analysis Dashboard

## Overview

This repository contains a sample hotel booking dataset for a data analysis dashboard, created for a freelancing project for a consulting agency in the hospitality industry. The agency seeks a Power BI dashboard with predictive analysis capabilities to gain insights into booking trends. The goal is to track seasonal patterns, cancellation rates by customer type, and average length of stay, with predictive analytics to forecast future booking trends. The dashboard focuses on three key areas, and a secondary page includes a forecasting component:

- **Seasonal Patterns**: Analyzing peak vs. low season bookings, cancellations, and guest demographics.
- **Cancellation Rates by Customer Type**: Evaluating cancellation trends across customer segments (e.g., transient, group).
- **Average Length of Stay**: Assessing stay duration by customer type, season, or other factors.
- **Predictive Analysis**: Forecasting future booking trends using Power BI’s forecasting tools.

## Repository Content

- `bookings_dataset.xlsx`: Dataset containing hotel booking data.
- `README.md`: This file, providing an overview and instructions.

## Data Description

The dataset contains the following columns, sourced from the Kaggle Hotel Booking Demand Dataset:

| Column Name                      | Description                                                                 |
|----------------------------------|-----------------------------------------------------------------------------|
| `hotel`                          | Type of hotel (e.g., Resort Hotel, City Hotel)                              |
| `is_canceled`                    | Indicates if the booking was canceled (1 = canceled, 0 = not canceled)      |
| `lead_time`                      | Number of days between booking and arrival                                 |
| `arrival_date_year`              | Year of arrival date                                                       |
| `arrival_date_month`             | Month of arrival date (e.g., January, February)                             |
| `arrival_date_week_number`       | Week number of arrival date                                                |
| `arrival_date_day_of_month`      | Day of the month of arrival date                                           |
| `stays_in_weekend_nights`        | Number of weekend nights stayed                                            |
| `stays_in_week_nights`           | Number of weekday nights stayed                                            |
| `adults`                         | Number of adults in the booking                                            |
| `children`                       | Number of children in the booking                                          |
| `babies`                         | Number of babies in the booking                                            |
| `meal`                           | Type of meal booked (e.g., BB = Bed & Breakfast, HB = Half Board)          |
| `country`                        | Country of origin of the guest                                             |
| `market_segment`                 | Market segment (e.g., Online TA, Offline TA/TO, Direct)                    |
| `distribution_channel`           | Booking distribution channel (e.g., TA/TO, Direct)                         |
| `is_repeated_guest`              | Indicates if the guest is a repeat customer (1 = yes, 0 = no)              |
| `previous_cancellations`         | Number of previous cancellations by the guest                               |
| `previous_bookings_not_canceled` | Number of previous non-canceled bookings by the guest                      |
| `reserved_room_type`             | Type of room reserved                                                      |
| `assigned_room_type`             | Type of room assigned at check-in                                          |
| `booking_changes`                | Number of changes made to the booking                                      |
| `deposit_type`                   | Type of deposit made (e.g., No Deposit, Non Refund, Refundable)            |
| `agent`                          | ID of the travel agency booking the reservation (if applicable)            |
| `company`                        | ID of the company booking the reservation (if applicable)                  |
| `days_in_waiting_list`           | Number of days the booking was on the waiting list                         |
| `customer_type`                  | Type of customer (e.g., Transient, Contract, Group, Transient-Party)       |
| `adr`                            | Average Daily Rate (revenue per occupied room)                             |
| `required_car_parking_spaces`    | Number of parking spaces requested                                         |
| `total_of_special_requests`      | Number of special requests made by the guest                               |
| `reservation_status`             | Reservation status (e.g., Canceled, Check-Out, No-Show)                    |
| `reservation_status_date`        | Date of the last status update                                             |


## Notes

- This dataset is sourced from the Kaggle Hotel Booking Demand Dataset, representing a sample of the hotel chain’s booking data. [Kaggle Hotel Booking Demand Dataset](https://www.kaggle.com/datasets/jessemostipak/hotel-booking-demand/data).
- Due to privacy concerns, the original dataset is not shared; this is a sample for analysis purposes.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.
