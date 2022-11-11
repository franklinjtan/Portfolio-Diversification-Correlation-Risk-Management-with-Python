# Correlation Matrix For My Portfolio
* I was curious to see if my investment porfolio hit the sweet spot between diversification and correlation, so I plotted the 5-year returns of my investments against SPY, used linear regression to calculate the beta and correlation, and generated a correlation matrix and a heatmap.
* I noticed that my investments have a long way to go to achieve what Ray Dalio describes as the "Holy Grail"

## Procedure
* Imported 5-Year adjusted closing prices of my stock investments using Yahoo Finance 
* Extracted percent change using NumPy
* Used linear regression to calculate slope (beta) and correlation
* Plotted % returns and linear regression line
* Created a correlation matrix and heatmap

## Screenshot of Graph Generated


## Libraries Used
* [Matplotlib](https://matplotlib.org/stable/tutorials/index)
* [NumPy](https://numpy.org/doc/stable/)
* [Pandas](https://pandas.pydata.org/)
* [SciPy](https://scipy.org/)
* [Seaborn](https://seaborn.pydata.org/)
