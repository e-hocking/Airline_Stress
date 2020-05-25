# Airline_Stress
Mathematic Model Minimize Airline Stress 

The model minimizes the stress to take a flight from New York City to San Francisco. <br> <br>
Variables included: <br> 
- which airport to leave from (ie EWR, JFK, LGA)
- which airline to take
- time of the flight <br>

Stressor Considered:
- Delays
- Cancellations
- Diverted Flights <br> <br>

The model determined the least stressful flight is from JFK on a Delta flight between 6am and 7am. <br>
In general it was found that an earlier flight would be least stressful probably since it isn't impacted by a backlog of flights. A flight later in the day could have an increased chance of being delayed if another flight was delayed in the day.

# Prerequites 
Gurobi, Python, Pandas

# Files
Airline_Stress.ipynb is the python file that computes the result for the mathematical mode through using the data from Data file <br>
<br>
Data.xlsx contains data scraped from a 2019 issue of Air Travel Consumer Report from the Office of Aviation Enforcement <br>
<br>
Minimizing Stress in Air-Travel.pdf contains the full research report that includes a discussion of various industries influences on the airline industry, the motivation of the model, it's applications and an analysis of the results <br>
