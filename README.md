# NYC Taxi Trip Analysis

This repository contains the analysis of NYC Taxi trip data. The goal of this analysis is to understand various aspects of the taxi operations, compare performance between different vendors, and provide recommendations for improvement.

## Dataset

The dataset used for this analysis is from the NYC Taxi & Limousine Commission (TLC) trip records. It includes information such as pickup and drop-off locations, trip distances, durations, fare amounts, and more.

## Analysis Overview

The analysis covers several key areas:

1. **Distribution of Trips by Vendor**:
   - Comparison of total trips, total fare amount, average trip distance, average trip duration, and average tip amount between Vendor 1 and Vendor 2.

2. **Peak Hours and Days**:
   - Identification of peak hours and days for taxi trips for both vendors.

3. **Top Pickup and Drop-off Locations**:
   - Identification of the top 10 pickup and drop-off locations for both vendors.

4. **Trip Characteristics**:
   - Analysis of trip distance and duration distributions.
   - Comparison of average trip distance and duration between vendors.

5. **Revenue Analysis**:
   - Analysis of total fare amount and tip amount distributions.
   - Comparison of total revenue and average tip amount between vendors.

## Key Findings

- **Vendor 2 Dominance**: Vendor 2 has significantly higher total trips and revenue compared to Vendor 1.
- **Peak Times**: The peak hours for trips are between 3 PM to 6 PM, and peak days are Tuesdays and Fridays.
- **Top Locations**: PULocationID and DOLocationID 74 and 75 are the most frequent pickup and drop-off locations for both vendors.
- **Trip Characteristics**: Vendor 2 has longer average trip distances and durations compared to Vendor 1.
- **Tip Amount**: Vendor 2 receives higher average tips than Vendor 1, indicating potentially better service quality.

## Recommendations

1. **Service Improvement for Vendor 1**:
   - Enhance service quality by training drivers and improving vehicle conditions.
   - Implement promotional strategies during peak hours and days.

2. **Expansion of Service Area**:
   - Vendor 1 should consider expanding their service area to include more high-demand locations.

3. **Efficiency Optimization**:
   - Optimize route planning and fleet management to improve operational efficiency.

## Files

- `NYC_Taxi_Trip_Analysis.ipynb`: Jupyter notebook containing the data analysis and visualizations.
- `analysed_dataset.xlsx`: The analysed dataset saved as an Excel file.
- `README.md`: This README file.

## Installation

To run the analysis, you need to have Python installed along with the following libraries:

- pandas
- numpy
- matplotlib
- seaborn
- scipy

You can install the required libraries using pip:

```bash
pip install pandas numpy matplotlib seaborn scipy
