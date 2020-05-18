# **etf-analysis**

### Simple financial analysis on the performance of some ETFs compared to the market and Gold (IAU) for personal use. 


Using Python/Pandas, analysis was conducted on:
 1. VDC
 2. IWF
 3. VNQ
 4. IVV (Market)
 5. IAU (Gold)
 6. LUBAX
 
### V.1.0.1 includes:
Inside is simple code for calculating (all data from Google Finance, for as far back as data was available): 
 1. Returns.
 2. Risk
     2.1 Box-plots
     2.1 Standard Deviations
     2.3 Variance, Covariance.
     2.4 Betas (Rolling, for as long as data was available for each individual asset).
 3. Correlations (tabled as well as in a heatmap).
 4. Sharpe Ratios (plotted as well).
 
 As well as commentary on some of the analysis.
 
 In the future this will be updated to include the information being pulled directly from an API instead of Google Finance. Additional calculations can be made and added in the future.