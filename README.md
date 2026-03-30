# Cyclistic Bike Share Data Analysis
SQL‑based analysis of 12 months of Cyclistic bike‑share data using BigQuery and Tableau.

## Overview

This project analyzes 12 months of Cyclistic bike‑share data to understand how casual riders and annual members differ in their usage patterns. The goal is to provide insights that support a marketing strategy aimed at converting casual riders into annual members.

## Background

This project is based on the Cyclistic bike-share case study from the Google Data Analytics Professional Certificate.

## Tools Used

SQL (BigQuery) — data cleaning, transformation, and analysis

Tableau — visualization and dashboarding

Excel / Sheets — initial exploration

## Dataset

The dataset contains 12 .csv files for each month of Cyclistic bike share trips from 2025

## Dashboard Preview

<img width="999" height="799" alt="Dashboard 1" src="https://github.com/user-attachments/assets/d3d429b7-082d-4480-a1d2-86205b6d6de9" />

## Business Task

The objective of this analysis is to identify and quantify the differences in usage patterns between casual riders and annual members of the Cyclistic bike‑share program. By examining how these two customer segments utilize Cyclistic’s services across key behavioral dimensions—such as ride duration, ride frequency, temporal patterns, and trip characteristics—the company aims to generate data‑driven insights that will inform the development of an effective marketing strategy.
The ultimate goal is to support Cyclistic’s strategic initiative to increase the number of annual memberships, which represent a more stable and profitable revenue stream. Insights derived from this analysis will guide the design of targeted marketing campaigns and promotional interventions intended to convert casual riders into long‑term subscribers.

## Report

The analysis is based on twelve months of historical trip data from the Cyclistic bike‑share program, made publicly available through the Divvy Bikes Data Portal. These datasets contain detailed, anonymized records of individual bicycle trips, including start and end timestamps, station locations, bike types, and rider categories (casual riders vs. annual members). All personally identifiable information has been removed to comply with applicable privacy and data‑protection standards.

The data is provided under a public license that permits use for analysis and reporting, with the requirement that no attempts be made to reidentify individual riders. The datasets are appropriate for this study because they offer comprehensive coverage of Cyclistic’s operations across an entire year, enabling a reliable comparison of usage patterns between customer segments. Minor limitations include occasional missing values, inconsistent station naming, and potential seasonal fluctuations, all of which have been addressed during the data cleaning and preparation stages.

### Analysis revealed:

- Casual riders take much longer trips than members. This is one of the core findings in the Cyclistic case study — casual riders behave more like tourists or leisure users, while members use bikes for short, frequent, utilitarian trips.

### Key Patterns

- Casual riders have longest rides on weekends (Sat/Sun ~25 min)
- Members have shorter, consistent rides (11–13 min)
- Weekday ride lengths drop for both groups

### Interpretation

This supports the idea that:

- Casual riders = leisure/weekend users
- Members = commuters / routine users

### Key Patterns

- Members take more rides on weekdays, especially Tue–Thu
- Casual riders peak on weekends
- Saturday is the only day where casual rides nearly match member rides

### Interpretation

Members rely on bikes for weekday commuting, while casual riders use them for weekend recreation.
Even though members take far more rides, casual riders accumulate more total hours because their rides are much longer.
This reinforces the idea that casual riders are more “experience‑oriented.”
Members take ~78% more rides than casual riders. This is expected — members use the service regularly, while casual riders use it occasionally.

✔ Members

- Take more rides
- Ride shorter durations
- Ride mostly on weekdays
- Likely use bikes for commuting

✔ Casual riders

- Take fewer rides
- Ride much longer durations
- Ride mostly on weekends
- Likely use bikes for leisure/tourism

