# Nigeria Power Crisis — Data Analysis & ML Forecasting

## Overview
End-to-end analysis of Nigeria's electricity sector using Python, 
covering economic costs, generation capacity, distribution performance, 
grid quality, and state-level access data from 2019–2024.

## Key Findings
- Nigeria loses $48bn/year to its energy crisis — more than the entire federal budget
- Only 31% of installed generation capacity is actually used
- The grid collapsed 8 times in 2024, double the 2019 figure
- Private generator capacity (42 GW) is now 10x larger than the actual grid (4.2 GW)
- Metering rate predicts payment rate with R²=0.95 — the single most actionable fix

## Tools & Libraries
Python · pandas · matplotlib · seaborn · scikit-learn · Jupyter

## Models Applied
| Model | Purpose | Result |
|-------|---------|--------|
| Linear Regression | Forecast crisis cost 2025–2027 | $55.4bn by 2027 |
| Polynomial Regression | Test for accelerating trend | R²=0.887, confirms acceleration |
| K-Means Clustering | Segment DisCos by performance | 3 tiers: Distressed / Developing / Performing |
| Linear Regression | Predict payment rate from metering | R²=0.95, 75% metering → 90.7% payment |

## Data Sources
Dataset independently compiled from NERC quarterly reports, TCN grid 
operations data, DisCo performance filings, CBN economic statistics, 
and World Bank energy access data.
