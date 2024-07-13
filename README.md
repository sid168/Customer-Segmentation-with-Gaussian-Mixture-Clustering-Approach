# Customer-Segmentation-with-Gaussian-Mixture-Clustering-Approach
Segment TravelTide customers using Gaussian Mixture Models to enhance retention through tailored rewards.

# Project Report: Customer Segmentation of TravelTide Customers

## Overview

TravelTide is an e-booking startup experiencing poor customer retention. The primary objective of this project is to enhance customer retention by implementing a Rewards Program. This program aims to understand customer behavior and assign appropriate perks to different customer segments.

## Customer Retention Strategy

### Goal
Encourage customers to sign up for the Rewards Program to boost retention.

### How the Rewards Program Works
1. **Understand Customer Behavior**: Analyze user data to understand their preferences and behaviors.
2. **Assign Perks**: Provide tailored perks to different customer segments based on their behavior.

## Methodology

### Deciding Cohort
We selected users who have had more than 7 sessions after January 4th 2023.


### Devising Metrics
Key metrics considered for understanding customer behavior include:
- **Demographics**: Gender, age
- **Booking Behavior**: Frequency of trips, advance booking duration, holiday season travel, family travel
- **Spending Habits**: Amount spent on flights and hotels, discount usage
- **Trip Characteristics**: Duration of stay, cancellation frequency, travel to/from home airport
- **Engagement**: Page clicks, session duration

### User-Level Metrics
Metrics aggregated at the user level:
- `user_id`
- `median_page_clicks`
- `num_sessions`
- `median_session_duration_seconds`
- `total_booked_trips`
- `num_cancelled_trips`
- `num_no_booking`
- `num_not_completed_trips`
- `num_completed_trips`
- `num_round_trip_flights`
- `num_one_way_flights`
- `total_flights_booked`
- `total_hotels_booked`
- `median_flight_discount_amount`
- `median_flight_base_price`
- `median_flight_spent`
- `median_hotel_spent`
- `median_hotel_discount_amount`
- `median_checked_bags`
- `median_seats_booked`
- `median_rooms`
- `median_days_until_departure`
- `median_days_until_checkin`
- `median_days_stay_flight`
- `median_night_stay_hotel`
- `num_times_travelled_from_homeairport`
- `num_times_travelled_to_homeairport`
- `num_times_travelled_from_outside_homeairport`
- `num_times_expensive_hotel_booked`
- `num_times_expensive_flight_booked`
- `num_weekend_trip`
- `num_holiday_season_trip`
- `avg_distance_flown`
- `gender`
- `age`
- `age_group`
- `married`
- `has_children`
- `home_country`

### Clustering Approach
Gaussian Mixture Model (GMM) was used to cluster the users into distinct groups. PCA was applied beforehand to reduce dimensionality and improve clustering efficiency.



