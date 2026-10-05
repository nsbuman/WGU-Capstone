# Predicting Hotel Booking Cancellations for Revenue Optimization
**Western Governors University - Data Analytics Capstone (D502)**

## Overview
This data analytics project utilizes historical hotel booking data to predict the likelihood of a customer canceling their reservation. By identifying high-risk bookings prior to the arrival date, hotel management can proactively implement strategic overbooking, adjust non-refundable deposit policies, and minimize unrecoverable revenue loss.

## Dataset
* **Source:** [Hotel Booking Demand](https://www.kaggle.com/datasets/jessemostipak/hotel-booking-demand) (Kaggle)
* **Size:** 119,390 records and 30 features (post-cleaning)
* **Target Variable:** `is_canceled` (Binary classification)

## Tech Stack
* **Language:** Python
* **Data Processing & ML:** Pandas, NumPy, Scikit-Learn (Random Forest Classifier)
* **Environment:** Jupyter Notebook, Linux (WSL)
* **Visualization:** Matplotlib, Seaborn, Tableau Public

## Key Findings & Results
* **Model Performance:** The Random Forest Classifier achieved an **89.42% overall accuracy** and an **82% recall** for identifying cancellations.
* **Business Impact:** The model successfully identified 7,241 true cancellations in the testing set with a low false-positive rate, providing the reliable predictive metrics required for capacity allocation and revenue management.
* **Primary Drivers:** Feature importance extraction revealed that `deposit_type`, `lead_time`, and `country` are the most significant behavioral predictors of a cancellation. 

## Project Deliverables
1. **[notebook.ipynb](notebook.ipynb):** The complete data preprocessing, feature engineering, and machine learning pipeline.
2. **[Tableau Dashboard](https://public.tableau.com/app/profile/nicholas.buman/viz/capstone_17911669073430/HotelBookingCancellationsTrendsPredictiveDrivers)** Interactive visual summary of geographical cancellation trends and predictive feature importance.
4. **Capstone Report:** Comprehensive documentation of the CRISP-DM methodology, statistical significance, and actionable business recommendations.
