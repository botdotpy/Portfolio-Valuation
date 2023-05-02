This is a stock porfolio valuation project completed on jupyter notebook. The project builds two portfolios with four stocks each. Namely: AMD, AAPL, MSFT and ORCL. The first porfolio is valued at $10,000, while the second one employs 10,000 porfolio simulations with the same stocks to determine an optimal weighting allocation that provides the best return (adjusted for risk).

Having imported two years historical data for the four stocks into a dictionary, the project calculates the normalized return for the first portfolio and assigns a weight of 0.25. Which is thereafter multiplied by the portfolio value ($10,000) to derive the portfolio's 'Position Values'.

Futhermore, a dictionary is created to store the stocks Position Values, alongside a column for 'Total' - the sum of each stock's postiion value per day. 

Using matplotlib.pyplot, the projects examines the porfolio's performance using a line chart to viewing a combined performance, then an individual performance of the stocks.
