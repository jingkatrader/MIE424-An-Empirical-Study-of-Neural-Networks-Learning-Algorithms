# MIE424-An-Empirical-Study-of-Neural-Networks-Learning-Algorithms


# Stock Prediction 
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
  - Tensorboard results: https://tensorboard.dev/experiment/B7s48DEIQpSbviQEgH8Tnw/


# Quantum Annealing
## Code file:
- Gradient Descent vs Quanntum_Annealing_for_convex_problem.ipynb
   - Install d'wave ocean package   
   - Create example binary linear regression problem
   - Solve the example problem using GD and projected GD
   - Solve the example problem using GD and projected GD
   - Solve the example problem using D'wave Simulated Annealing   
   - Connect to D'wave quantum annealer, Dwave account set up (instructions provided) 
   - Solve the example problem using Quantum Annealing
   - Time complexity comparisons
   - Accuracy comparisons

# CIFAR-10 Image Classification
## Code file:
- Image Classification.ipynb 
   - Data processing:
      - Load CIFAR-10 dataset and apply one-hot-encoding 
      - Split dataset into train (70%), validation (14%), and test (16%) sets
   - Build a self-defined training method 
      - Test_optimizer() can run for all six learning algorithms 
   - Experiment 3 learning algorithms (included in Tensorflow packages): 
      - Adam
      - Adagrad
      - SGD 
   - Self-implemented 3 learning algorithms (not included in Tensorflow packages): 
     - SGD Average
     - SGD Noise
     - Adam Noise
   - Tensorboard
      - Connect to Tensorboard to track training and validation process 
      - View our Image Classification Tensorboard at:  https://tensorboard.dev/experiment/QHeHnU1VRFWoPBSKepSzHg/

