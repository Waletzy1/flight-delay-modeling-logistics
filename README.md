# US Flight Delay Modeling & Logistic Regression Analysis

This project applies data science and programming techniques to analyze large-scale airline delay data from 1996–2000, with the goal of identifying delay patterns and predicting flight diversions.

## Overview

The objective was to evaluate temporal patterns in flight delays, aircraft aging effects, and build logistic regression models for predicting flight diversion risks.

## Dataset

- Source: Harvard Dataverse (1996–2000)
- Size: 120M+ records (sampled down for EDA)
- Merged with aircraft metadata by tail number
- Features: CRS times, delay minutes, distance, plane age, carrier, etc.

## Questions Answered

1. What are the best times and days of the week to minimize delays?
2. Do older planes experience more delays?
3. What factors predict whether a flight will be diverted?

## Techniques Applied

- Data Preprocessing (R & Python): Sampling, cleaning, joining datasets
- Exploratory Data Analysis (EDA): Delay trends by hour/day, plane age
- Feature Engineering: Plane age groupings, total delay metrics
- Modeling:
  - Logistic Regression (Diverted vs Non-diverted)
  - Visualization of coefficients across years
  - Evaluation using McNemar's test, specificity, sensitivity

## Key Insights

- Best time to avoid delays: 1AM–5AM
- Best days: Tuesdays & Saturdays
- Older aircraft tend to have longer delays
- Flight diversions are significantly associated with carrier and weekday

## Tools & Languages

- **R**: tidyverse, broom, ggplot2, corrplot
- **Python**: pandas, seaborn, matplotlib, numpy, sklearn

## Business Value

This analysis helps airlines optimize flight schedules, manage fleet usage more effectively, and reduce delay/diversion costs by understanding underlying delay patterns.

## Author

**Seow Xin Yong**  
BSc (Hons) Data Science & Business Analytics  
University of London @ SIM  
[LinkedIn](https://www.linkedin.com/in/seow-xin-yong/)
