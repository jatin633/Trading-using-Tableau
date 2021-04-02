# Trading-using-Tableau
stock.twb is a tableau file with five objectices

1: Volatility index that ranks stocks based on intraday price movements. (this is a candelstick graph)

2: Complete Stock Price Analysis for PCLN Stock. (Complete detailed graph of PCLN stock from start to end date)

3: Top 10 Stock for the entire duration. (this is a running chart and provide top 10 stock from start to end date)

4: Pair Trading -- Top 5 pair trading stock from 2013 to 2017. (Pair trading stock means that they are moving together as a pair according to their stock price open,close and low)

5: Prediction Chart of AZO Stock. (AZO (1).csv is a subset of data.csv and provide the future prediction cost of stock based on previous up and down)

# important formulas --> 
 High Low -- SUM([Low]) - SUM([High])   
 Open Close -- SUM([Close]) - SUM([Open]) 
 rank -------RANK_UNIQUE(SUM([Close]))
 Future Prediction --- if [Close] < [Open] THEN 0 ELSEif [Close] > [Open] THEN 1 END
 These formulas are used to analyse the fluctuation that come in the price of stocks.
