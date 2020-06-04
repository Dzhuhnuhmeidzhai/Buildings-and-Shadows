I was not able to tackle this problem due to unforeseen circumstances.

However, my approach to this problem is:-

1. Simulate data (daily new cases curves) of various kinds:-
a. yet to reach peak
b. reached peak
c. crossed peak and descended

2. Train stock-market predicting algorithms (time-series algorithms like ARIMA) on this generated data because stock-market prediction
algorithms do not predict based on local trends in the curve and take into account seasonality and
other factors. 

3. Also take into account, current active cases at each time-step since the number of people that can be infected in one day
is proportional to the number of active cases on that day.
