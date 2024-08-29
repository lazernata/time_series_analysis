# Time Series Modeling: Classical Models and SARIMA

This repository contains the practical part of my Master's Thesis titled **"Time Series Modeling: Classical Models and SARIMA"**, as part of the Master's in Applied Statistics at the University of Granada.

In this work, the Box-Jenkins methodology is implemented to model and forecast time series, specifically using data on the monthly average temperature in Jersey Island. Various steps are taken to identify and fit appropriate SARIMA models for making accurate predictions.

## Contents

The repository includes four RMarkdown (`.md`) files, each detailing different stages of the Box-Jenkins methodology for time series modeling:

1. **1. Identification.md**: 
   - **Description**: This file covers the first stage of the Box-Jenkins methodology, **Identification**. The monthly average temperature time series is analyzed to determine if it is stationary and whether differencing is required. The potential orders of the autoregressive (AR) and moving average (MA) components are identified using ACF and PACF plots.

2. **2. Estimation.md**: 
   - **Description**: This file describes the **Estimation** of the SARIMA model parameters. After identifying a potential model, the parameters are estimated using the maximum likelihood method. The estimation results are presented, and the significance of the coefficients is discussed.

3. **3. Validation.md**: 
   - **Description**: This section covers the **Diagnosis** of the fitted model. The assumptions of the SARIMA model, such as the independence, normality and randomness of residuals, are checked using statistical tests and graphical analysis.

4. **4. Forecast.md**: 
   - **Description**: Finally, this file presents the **Predictions** made with the selected model. The fitted models are used to forecast the monthly average temperature for a future period. Additionally, the predictions are compared with the actual observations to assess the model's accuracy.

## Requirements

To replicate the analysis contained in these files, you will need to have:

- [R](https://cran.r-project.org/)
- [RStudio](https://rstudio.com/)
- Required R packages:
  - `forecast`
  - `tseries`
  - `ggplot2`
  - `fUnitRoots`
  - `TSA`
  - `lmtest`
