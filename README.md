 **# Flight Ticket Fare Prediction**

**## Overview**

This project delves into the complex world of airline pricing and develops a predictive model to accurately estimate flight ticket fares. It aims to assist travelers, airlines, and online travel agencies in making informed decisions and optimizing pricing strategies.

**## Problem Statement**

The airline industry is characterized by dynamic pricing influenced by various factors, including:

- **Airline-specific factors:** Carrier, seating classes, amenities, pricing strategies
- **Passenger preferences:** Direct flights, conveniences, travel time
- **Partner influences:** Hotel, taxi, connecting flight options
- **Booking considerations:** Timing, limited capacity, demand

The goal is to create a robust model that effectively predicts flight ticket prices based on diverse quantitative and qualitative features, providing valuable insights for stakeholders.

**## Dataset Description**

* **Files:**
  * `Train.xlsx`: Training dataset containing features and ticket prices
  * `Test.xlsx`: Unlabeled test dataset for model evaluation
  * `SampleSubmission.csv`: Template for submitting predictions
* **Features:**
  * Date/time-related features (e.g., booking date, travel date, flight duration)
  * Quantitative features (e.g., number of stops, flight distance)
  * Qualitative features (e.g., airline, departure/arrival cities, flight type)
* **Target Attribute:** `ticketprice`

**## Evaluation Metric**

* **MAPE (Mean Absolute Percentage Error)** is the primary metric to assess model accuracy, emphasizing relative error for better interpretability.

**## Model Performance**

* Decision Tree and Post-Pruned Decision Tree models achieved:
   * R-squared: ~0.90
   * MAPE: ~0.095

**## Contributions**

Contributions are welcome! Please feel free to submit issues, pull requests, or contact the project maintainers.
