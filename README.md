# Hotel Booking Demand - Dataset Exploration

## Dataset Overview
The Hotel Booking Demand dataset contains booking information for city and resort hotels. It includes details such as booking dates, customer information, stay duration, room type, and booking cancellation status.

## Business Problem
Hotels often face revenue loss due to booking cancellations. Predicting cancellations can help hotels improve room allocation and reduce financial losses.

## Machine Learning Problem
**Classification**

### Justification
The objective is to predict whether a booking will be cancelled (`is_canceled`) or not. Since there are two possible outcomes (0 = Not Cancelled, 1 = Cancelled), this is a classification problem.

## Target Variable
- is_canceled

## Key Features
- hotel
- lead_time
- arrival_date_month
- adults
- children
- country
- previous_cancellations

## Three Key Observations
1. The dataset contains missing values in columns such as `country`, `agent`, and `company`.
2. The dataset includes bookings for both City Hotels and Resort Hotels.
3. The booking lead time varies significantly, which may influence cancellation rates.
