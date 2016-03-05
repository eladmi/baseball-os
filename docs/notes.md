# Baseball OS

A set of command-line tools that allows a user to create, and run a baseball simulation, and extract all kinds of data and information from the resulting runs.

## Design principles

1. The simulations are not interactive
  a. Configuration files allows user to define starting conditions
  b. Simulations produce data output
  c. Command-line tools are used to interact with data
2. Start simple and grow steadily more complex
3. Each tool should do one thing well

## Miscellaneous

* Pitcher 
  * fatigue = pitch count/expected pitch count
  * days off = int(sqrt(4*innings pitched) - 1.4)
* Interactive mode as a command-line interface?
* Pi
