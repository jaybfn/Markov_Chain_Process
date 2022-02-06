# Estimation of customer behaviour in a supermarket using a Markov model

### Using point-of-sale data, several research have been dedicated to understanding the customer's purchase decision process. In order to better understand consumers' in-store behavior, a few recent studies acquired customer shopping route data utilizing radio frequency identification technology in addition to point-of-sale data. Consumer shopping route data, on the other hand, just provides store coordinates, whereas an estimate of customer behavior is required. In this project, I'm attempting to predict consumer behavior using a Markov model, which is commonly used to estimate several states of customer behavior in supermarkets.

# Tech Stack

### Python 3.9

# Data

### 1. It contains.csv files for consumer location in the supermarket from open to closetime from Monday to Friday. Also, when the store shuts and customers who did not checkout stay in the supermarket, we must make a note of this (need to consider this info to avoid any glitch in prcessing the data).
### 2. the csv files contains customer_no which resets everyday , section: which shows the loc of each custmoer in the supermaket and associated time to it.

# python scripts

### 1. Supermarkek_customer_data_EDA.ipynb: this is for visualizing customer data
### 2. Transition_probablities.ipynb: transition probablities calculated for monday.csv and generated a synthetic dataset for the supermaket using those probabilities.
