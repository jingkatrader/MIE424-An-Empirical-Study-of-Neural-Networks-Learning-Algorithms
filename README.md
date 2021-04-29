# MIE424-An-Empirical-Study-of-Neural-Networks-Learning-Algorithms


## Data files:
- data_more.xlsx:     
consists of the stock prices for BSE SENSEX index from Jan 1991 - Dec 2020    
- data_feature_more.xlsx:    
consists of the computed 10 stock indicators for BSE SENSEX index


## Code files:
- data_cleaning.ipynb:    
   - Process the historical stock prices using the same 10 traditional technical analysis formulas per mentioned in paper "Predicting stock and stock price index movement using Trend Deterministic Data Preparation and machine learning techniques"
   - Save the computed stock indicators into data_feature_more.xlsx which will be used as input features in the prediction models (ANN, Random Forest)

- RandomForest.ipynb:
  - Baseline model for stock price movement prediction
  - Use 100 trees, each with 500 nodes

- MIE424-ANN_Stock_Prediction.ipynb:
  - Use a 4 layer ANN model to predict future stock price movement
  - Explore three learning algorithms:
    - Adam: An algorithm for first-order gradient-based optimization of stochastic objective functions, based on adaptive estimates of lower-order moments.
    - Adagrad: A subgradient methods that dynamically incorporate knowledge of the geometry of the data observed in earlier iterations to perform more informative gradient-based learning.
    - SGD: A stochastic approximation of gradient descent optimization by estimating a randomly selected subset of the data
