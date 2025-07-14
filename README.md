# British Airways: Customer Booking Completion Insights

This project develops a predictive model to identify customers likely to complete bookings, helping optimize marketing and improve conversion rates.

## Model Performance
- Overall Booking Completion Rate: 15%
- Accuracy: ~86%
- Precision: ~55%
- Recall: ~13% (needs improvement)
- AUC-ROC Score: ~0.79

## Key Drivers
Top features influencing booking completion include purchase lead time, length of stay, flight hour/day, and booking origin.

## Customer Behavior Insights
- Most bookings come from the internet, with mobile also significant.
- Round trips dominate bookings.
- Shorter stays have higher completion rates.
- Geographic location affects booking behavior.

## Next Steps
- Increase positive samples to improve recall.
- Tune model hyperparameters.
- Explore alternative models like LightGBM or XGBoost.
- Enhance feature engineering.

*Note:* Interactive charts from the original HTML cannot be shown in Markdown. Use GitHub Pages to host the HTML for full interactivity.

## Lounge Eligibility Lookup Table

This notebook focuses on forecasting British Airways lounge demand at Heathrow Terminal 3 by creating a reusable lookup table. The table estimates the percentage of passengers eligible for different lounge tiers based on flight groupings by time of day and haul type. The approach involves analyzing historical flight data, testing various grouping methods, and validating the model's predictive power. Key assumptions include consistent passenger behavior and the primary influence of time and haul on lounge eligibility. The final output includes CSV and Excel files for operational use, providing a scalable and practical tool for capacity planning.
