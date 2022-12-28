# Portfolio Diversification: Correlation Risk Management with Python
* Understanding the importance of diversification and a portfolio of uncorrelated returns, I plotted the 5-year returns of several equities, ETFs, and commodities against SPY.
* I also used linear regression to calculate the beta and correlation, and generated a correlation matrix and a heatmap.

## Procedure
* Imported 5-Year adjusted closing prices of my stock investments using Yahoo Finance 
* Extracted percent change using NumPy
* Used linear regression to calculate slope (beta) and correlation
* Plotted % returns and linear regression line
* Created a correlation matrix and heatmap

## Screenshot of Maxtrix and heatmap Generated
![Correlation Matrix](/images/correlation_matrix.png)
![Heatmap of Portfolio](/images/heatmap.png)

## Inspiration
* David Ng, Professor of Finance, Cornell University - Taught my Finance Analytics Class
* Principles by Ray Dalio
* [Ray Dalio Breaks Down His Holy Grail](https://www.youtube.com/watch?v=Nu4lHaSh7D4)
* [YT Tutorial: Calculating the Correlations Between Stocks Using Python by Kevin Mooney](https://www.youtube.com/watch?v=Oa7br3Okxac)

## Libraries Used
* [Matplotlib](https://matplotlib.org/stable/tutorials/index)
* [NumPy](https://numpy.org/doc/stable/)
* [Pandas](https://pandas.pydata.org/)
* [SciPy](https://scipy.org/)
* [Seaborn](https://seaborn.pydata.org/)
