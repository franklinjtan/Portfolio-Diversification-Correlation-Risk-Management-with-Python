# Analyzing My Portfolio For Diversification Using Correlation Matrix in Python
* I was curious to see if my investment porfolio hit the sweet spot between diversification and correlation, so I plotted the 5-year returns of my investments against SPY, used linear regression to calculate the beta and correlation, and generated a correlation matrix and a heatmap.
* I concluded that my investments have a long way to go to achieve what Ray Dalio describes as the "Holy Grail". I will be identifying 10 uncorrelated stocks to increase my return-to-risk ratio

## Procedure
* Imported 5-Year adjusted closing prices of my stock investments using Yahoo Finance 
* Extracted percent change using NumPy
* Used linear regression to calculate slope (beta) and correlation
* Plotted % returns and linear regression line
* Created a correlation matrix and heatmap

## Screenshot of Maxtrix and heatmap Generated
![Correlation Matrix](/images/correlation_matrix.png)
![Heatmap of Portfolio](/images/portfolio_heatmap.png)

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
