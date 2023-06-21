# WSC-Task
The code simulates the stock price paths of three different stocks: HDFC, ICICI, and ITC. It uses a geometric Brownian motion model, which incorporates both deterministic drift and stochastic (random) fluctuations, to generate the variations in stock prices over time.

The code begins by defining the names of the stocks, their mean returns, and standard deviations. It then calculates the overall drift and standard deviation based on the weighted sum of the individual stock parameters.

Next, the simulation parameters are set, including the drift, number of steps (representing the number of working days in a year), time horizon, number of simulations, standard deviation, and initial stock price.

The stock price paths are simulated using a loop. Within the loop, the code iterates over each simulation and generates the stock prices at each time step. It uses the geometric Brownian motion equation, incorporating the drift and stochastic component, to calculate the next price based on the previous price. The simulation continues until the total time horizon is reached.

After simulating the stock price paths for all the simulations, the code plots the paths using the matplotlib library, visualizing how the stock prices evolve over time.

The code provides a useful framework for simulating and visualizing stock price paths based on mean returns and standard deviations. It can be modified and expanded to incorporate additional features or used as a starting point for further analysis in the field of quantitative finance.
