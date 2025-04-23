# FederalFundsRate
Predicting U.S. economic indicators using the Federal Funds Rate with neural networks (MLP Regressor). A data-driven macroeconomic analysis of inflation, GDP, and more.
# Federal Funds Rate Impact on U.S. Economy

This project explores how adjustments to the **Federal Funds Rate (FFR)** influence key U.S. economic indicators such as **inflation**, **GDP**, **unemployment**, and the **velocity of M2 money supply**. Using historical data from 1960 to present, we applied a **Multi-Layer Perceptron Regressor (MLP)**—a type of neural network—to test the predictive power of the FFR.

## Project Highlights
- **Lag Analysis**: Identified optimal lag periods between FFR changes and economic variable responses.
- **Machine Learning**: Implemented **MLPRegressor** from `scikit-learn` to detect nonlinear relationships.
- **Key Findings**:
  - Inflation measures (especially **PCE**) showed moderate predictive correlation (R² ≈ 0.53).
  - GDP and RGDP were moderately predictable (~50% accuracy).
  - **Unemployment** and **M2 Velocity** were poorly predicted using FFR alone.

## Methods
- **Libraries**: `pandas`, `scikit-learn`, `seaborn`, `matplotlib`
- **Models**: Multi-Layer Perceptron with 3 hidden layers (200, 100, 50 neurons).
- **Evaluation**: R² scores, correlation matrices, heatmaps.

## Data Sources
- **Federal Reserve Economic Data (FRED)**: [https://fred.stlouisfed.org](https://fred.stlouisfed.org)
- Quarterly economic indicators including CPI, PCE, PPI, GDP, RGDP, UNEMP, and M2.

## Key Takeaways
- The **Federal Funds Rate** is a significant but not sole predictor of macroeconomic trends.
- Time lags vary: Inflation responds within **2 quarters**, unemployment within **8-9 quarters**.
- Additional variables (e.g., fiscal policy) are necessary for more accurate forecasting.

## Contributors
- William Pettit (Finance, 2023)
- Mira Pölzer (Economics, IT, Business Analytics 2025)
- Matthew Zawaski (Finance, 2023)

## Future Improvements
- Integrate other monetary tools (e.g., reserve requirements, open market operations).
- Compare neural network models with **linear regression** or **ARIMA**.
- Increase data frequency for higher-resolution forecasting.

---

This project was part of a collaborative undergraduate research initiative focused on applying machine learning techniques to real-world economic challenges.
Read the Paper: https://docs.google.com/document/d/10RzEx6FQFFsJZknk-eHnKSi0rMcf3Ug-hT9HHnjSBmQ/edit?usp=sharing
