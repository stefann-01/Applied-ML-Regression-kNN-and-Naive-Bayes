# Applied ML: Regression, k-NN, and Naive Bayes

A comprehensive project exploring polynomial regression, k-NN classification, and Naive Bayes text classification through practical implementations and analysis.

## Problem Descriptions

### Problem 1: Research
- **Task**: Investigate and understand the concepts of Word2Vec, Naive Bayes methods, and linear separability.
- **Output**: Answers are provided in a text file.

### Problem 2: Regression
- **Task**: Predict ocean water temperature based on salinity using polynomial regression.
- **Dataset**: `bottle.csv`
- **Details**:
  - Implement polynomial regression with degrees ranging from 1 to 6.
  - Apply polynomial regression with L2 regularization, experimenting with different lambda values.

### Problem 3: k-NN Classification
- **Task**: Classify iris flower species based on their features using k-NN.
- **Dataset**: `iris.csv`
- **Details**:
  - Implement k-NN using the first two features for k=3.
  - Evaluate k-NN accuracy for k values from 1 to 15.
  - Use all features for k-NN and compare results.

### Problem 4: Text Classification / Naive Bayes
- **Task**: Classify tweets as disaster-related or not using Multinomial Naive Bayes.
- **Dataset**: `disaster-tweets.csv`
- **Details**:
  - Clean the dataset and create feature vectors.
  - Achieve at least 65% accuracy on the test set.
  - Identify and analyze the most common words in positive and negative tweets.

## Running the Project
1. Ensure you have the required dependencies installed.
2. Run the provided Python scripts for each task in the respective order.
3. Review the output graphs and comments for insights and analysis.

## Dependencies
- Python 3.x
- Required libraries: `numpy`, `pandas`, `scikit-learn`, `matplotlib`

## Notes
- Each task's implementation is self-contained within its respective script.
- Comments and explanations are provided within the scripts for better understanding.
