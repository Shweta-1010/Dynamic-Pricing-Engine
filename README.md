#  Dynamic Pricing Engine

An AI-powered dynamic pricing engine for e-commerce, leveraging machine learning models like XGBoost and reinforcement learning to adjust prices in real time based on demand fluctuations.

## Features

-  Machine Learning-Based Pricing – Uses XGBoost with hyperparameter tuning to predict optimal prices.
-  Reinforcement Learning for Price Optimization – Adapts prices dynamically to maximize revenue.
-  Real-Time Updates – Prices are updated dynamically on the frontend using Firebase.
-  Flask API for Integration – Handles price adjustments via POST requests.
-  Future Enhancements – Plans to integrate SARIMA and GARCH models for time-series forecasting

## Tech Stack

- Frontend: HTML, CSS, JavaScript
- Backend: Node.js, Flask (API)
- Database: MongoDB
- Machine Learning Models: XGBoost, Reinforcement Learning
- Cloud Services: Firebase (for real-time updates)

## How It Works
- Data Collection – Uses historical pricing, demand, and market conditions.
- Price Prediction – XGBoost predicts optimal prices based on input features.
- Reinforcement Learning – Adjusts pricing dynamically based on real-time feedback.
- Real-Time Updates – Firebase updates the website with new pricing.
- API Integration – Flask API allows external systems to request price updates.

## Results & Performance
-  Achieved 90%+ prediction accuracy using XGBoost with hyperparameter tuning.
-  Plans to integrate SARIMA & GARCH for time-series price forecasting.

## Future Enhancements
-  Implement SARIMA and GARCH models for better price trend analysis.
-  Extend support for multiple e-commerce platforms.
-  Optimize real-time pricing using deep reinforcement learning.
