# CD Interest Rate Simulation


Here a model is developed to set interest rate on a new 3-month CD that a bank wants to roll out. In order to set the rate, this project computes the potential range of 3-month interest rate in the future.

Today’s interest rate is 5%, and changes in interest rate follow a lognormal process with mean zero a standard deviation of 0.625% a day.
The Jupyter notebook, simulate and graph 10 interest rate scenarios path with daily interval for the next 90 days.
As a result, regardles of monetary policy decisions to cut or raise intrest rates, we project the potential paths of 10 scenarios given the historical variability of CDs provided by the standard deviation parameter of 0.625% a day

Project Input
- Input: Historical standard deviation of CDs: key metric to understand interest rate variability 
- Output: Algorithm that computes that variability into a lognormal process with mean zero and a line chart predicting 10 potential paths interest rates might take in the next 90 days. 

Please, refer to this page to undertand the lognormal process for interest rates: https://en.wikipedia.org/wiki/Log-normal_distribution

Lognormal Simulation Additional Contest: https://medium.com/@polanitzer/the-lognormal-model-in-python-predict-the-bank-of-israel-interest-rate-one-year-ahead-using-the-6773eac79f5d

#Interest Rate Simulation Chart
