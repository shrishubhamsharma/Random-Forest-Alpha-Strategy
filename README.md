# Random Forest Alpha Strategy — Emerging Markets

## Project Overview
Multi-market quantitative Alpha strategy using Random Forest 
to identify investment opportunities across Emerging Markets.
Includes ROC curve analysis to measure signal quality.

## Markets Analyzed
- Brazil (EWZ)
- India (INDA)
- Turkey (TUR)
- South Africa (EZA)

## Features Engineered
- Daily Returns — momentum continuation signal
- 5-day Moving Average — short term trend
- 20-day Moving Average — medium term trend
- 10-day Rolling Volatility — market stress detection
- 5-day Momentum — weekly price acceleration

## Model
- Algorithm: Random Forest Classifier (100 trees)
- Training: 80% chronological split
- Testing: 20% out-of-sample data
- Evaluation: Accuracy + ROC AUC Score

## Results
| Market      | Accuracy | AUC   |
|-------------|----------|-------|
| Brazil      | 52.02%   | 0.525 |
| India       | 48.79%   | 0.491 |
| Turkey      | 51.21%   | 0.520 |
| South Africa| 48.39%   | 0.485 |

## Key Finding
Technical features alone insufficient for consistent 
Alpha generation. Macro factors — interest rates, 
currency volatility, commodity prices — needed for 
production-grade EM signal.

## Tools Used
- Python, Pandas, NumPy
- Scikit-learn (Random Forest, ROC Analysis)
- Matplotlib
- yfinance

## Author
Shubham Sharma
Quantitative Investment Engineer
linkedin.com/in/shrishubhamsharma
