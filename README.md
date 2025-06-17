# Hotel Booking Data Analysis

## Project Overview
This project dives deep into hotel booking data to uncover the real story behind reservations, cancellations, and pricing. Our goal is to truly understand customer behavior – why they book, why they cancel, and what influences their decisions. By revealing these key patterns, we aim to deliver actionable insights that directly improve how our hotels operate and help us sharpen our business strategies.

## Data Source
The primary dataset used for this analysis is `hotel_booking.csv`, which contains detailed information about hotel reservations. Additionally, the project includes functionality to interact with a MongoDB database, specifically connecting to a database named `Python_Data_Analysis` and a collection named `Hotel Booking`, suggesting potential data ingestion or further data storage.

## Methodology
The analysis is performed using Python and leverages several powerful libraries for data manipulation, analysis, and visualization.

Key steps involved:
1.  **Data Loading:** Efficiently loading large datasets in chunks from the CSV file.
2.  **MongoDB Integration:** Establishing a connection to MongoDB for potential data storage or retrieval.
3.  **Data Cleaning and Preparation:** Addressing inconsistencies and preparing the data for analysis.
4.  **Exploratory Data Analysis (EDA):** Investigating trends related to:
    * Average Daily Rate (ADR) over time.
    * Analysis of booking cancellations versus non-cancellations.

## Tools and Libraries
* **Python**
* **pandas:** For data manipulation and analysis.
* **pymongo:** For interacting with MongoDB.
* **matplotlib & seaborn:** For data visualization.

## Key Insights (High-Level)
While specific numerical results and detailed visualizations are generated within the Jupyter Notebook, the analysis focuses on understanding:
* Fluctuations and trends in Average Daily Rate.
* Factors influencing hotel booking cancellations.

## How to Run
1.  Ensure you have Python and the necessary libraries installed (`pandas`, `pymongo`, `matplotlib`, `seaborn`).
2.  (Optional) Set up a MongoDB instance if you wish to utilize the database integration.
3.  Place `hotel_booking.csv` in the same directory as the `Hotel data analysis.ipynb` notebook.
4.  Run the `Hotel data analysis.ipynb` notebook using a Jupyter environment.
