# Factors Affecting U.S. Gross Domestic Saving Rate (1975–2021)

## Abstract
This project examines the determinants of the U.S. gross domestic saving rate (% of GDP) between 1975 and 2021. Using World Bank data and econometric techniques, the study investigates the influence of four macroeconomic variables: real interest rates, inflation, age dependency ratio, and GNI per capita. Results indicate that the age dependency ratio and real interest rates have significant negative long-run effects on saving rates, while GNI per capita and inflation show no significant long-run impact.

## Data
- Source: World Development Indicators, World Bank (1975–2021)
- Observations: 47 annual data points
- Variables:
  - Gross Domestic Savings (% of GDP)
  - GNI per capita (USD, Atlas method)
  - Age dependency ratio (%)
  - Inflation (CPI, %)
  - Real interest rate (%)

## Methodology
1. **OLS Regression**
   - Verified assumptions: linearity, no multicollinearity, zero conditional mean, homoscedasticity, no autocorrelation, normality.
   - Diagnostic tests: VIF, Ramsey RESET, Breusch–Pagan, White’s test, Durbin–Watson, Skewness–Kurtosis.

2. **Stationarity and Cointegration**
   - Augmented Dickey–Fuller test confirmed variables are I(1).
   - Johansen cointegration test identified two cointegrating vectors.

3. **Vector Error Correction Model (VECM)**
   - Long-run effects: dependency ratio and real interest rates significantly reduce savings.
   - Short-run effects: limited significance, but the error correction term indicates adjustment toward equilibrium.

## Key Findings
- **Age Dependency Ratio**: Significant negative long-run effect. Higher dependency reduces saving capacity.
- **Real Interest Rate**: Significant negative long-run effect. Higher real rates may deter saving when linked to financial instability.
- **Inflation**: Negative but not significant in the long run.
- **GNI per Capita**: No significant long-run relationship with saving rate.

## Policy Implications
- Reform pension systems and support workforce participation to address demographic pressures.
- Maintain macro-financial stability and trust in monetary policy to encourage saving.
- Recognize that income growth alone does not guarantee higher national saving rates.

## Skills Demonstrated
- Econometric modeling (OLS, VECM)
- Time-series analysis (ADF, Johansen test)
- Model diagnostics (RESET, Breusch–Pagan, White, Durbin–Watson)
- Interpretation of econometric results for policy insights
- Tools: STATA, Excel

## Project Structure
- `report.pdf` – Full research paper
- `figures/` – Key charts and model outputs
- `data_sources.txt` – Data reference (World Bank WDI)

## Future Research
- Account for structural breaks (e.g., 2008 financial crisis, COVID-19 pandemic).
- Explore nonlinear models such as threshold regressions.
- Extend analysis using panel data across multiple countries.
