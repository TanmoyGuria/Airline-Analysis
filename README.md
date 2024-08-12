# Airline Occupancy Analysis

This project focuses on analyzing airline occupancy data to improve seat utilization and increase average profit per seat. The analysis is performed using Python and SQL, with data stored in an SQLite database.

## Table of Contents

- [Overview](#overview)
- [Data](#data)
- [Analysis](#analysis)
- [Requirements](#requirements)


## Overview

The Airline Occupancy Analysis project aims to identify patterns and trends in airline occupancy data to optimize seat allocation and boost revenue. The analysis leverages Python's data processing capabilities and SQL queries to extract meaningful insights from the SQLite database.

## Data

The dataset is stored in an SQLite database file named `airline_data.db`. The database contains tables with information on:

- Flight schedules
- Passenger bookings
- Seat occupancy rates
- Revenue metrics

## Analysis

The analysis includes the following steps:

1. **Data Extraction**: Using Python's `sqlite3` connector to query and retrieve data from the SQLite database.
2. **Data Processing**: Cleaning and transforming the data for analysis.
3. **Exploratory Data Analysis (EDA)**: Identifying patterns, trends, and anomalies in the occupancy rates and revenue metrics.
4. **Visualization**: Creating visualizations to illustrate findings and support decision-making.
5. **Insights**: Formulating actionable recommendations to improve occupancy rates and revenue.

## Requirements

- Python 3.x
- sqlite3 (included with Python)
- pandas
- matplotlib
- seaborn
