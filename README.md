## Temperature modelling with Ornstein-Uhlenbeck process
Features
* Models fitted into historical temperature data from Lincolnshire, England
* Baseline temperature: seasonality modelled via Fourier Series, while interannual trend is fitted via linear regression
* O-U parameters: rate of mean reversion $\theta$ is extracted from lagged residuals plot
* Volatility decomposed into seasonal + interannual + residuals (still under refinement)
* Simulation implemented using Euler-Maruyama discretisation of the O-U process

Issues
* Volatility model to be improved as simulated volatility seems to be much less than expected (31 Aug 2025)
