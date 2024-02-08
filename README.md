# Week-14-Homework
Python Notebook and responses to homework questions + screenshots.

## Step 1: Tune the training algorithm by adjusting the size of the training dataset.
### To do so, slice your data into different periods. Rerun the notebook with the updated parameters, and record the results in your README.md file. Answer the following question: What impact resulted from increasing or decreasing the training window?

# Baseline Dataplot to Compare Against
<img width="452" alt="baseline " src="https://github.com/rjudd9/Week-14-Homework/assets/134743177/9ddea77e-9f40-4419-b158-c21764f23637">

### Answer: By increasing the training window, the predictions became closer to the actual returns.

## Step 2: Tune the trading algorithm by adjusting the SMA input features.
### Adjust one or both of the windows for the algorithm. Rerun the notebook with the updated parameters, and record the results in your README.md file. Answer the following question: What impact resulted from increasing or decreasing either or both of the SMA windows?

### Answer: By increaseing both the short and long windows, I can see a longer comparison of actual returns to strategy returns. 

# Step 3: Choose the set of parameters that best improved the trading algorithm returns.
## Save a PNG image of the cumulative product of the actual returns vs. the strategy returns, and document your conclusion in your README.md file.

# Adjusted Windows
<img width="466" alt="adjusted window" src="https://github.com/rjudd9/Week-14-Homework/assets/134743177/5640c908-fd96-445e-9e76-9275780132a6">

### Answer: By increaseing the short term window to 12 and the long term window to 300, I can see the strategy returns chart the actual returns quite accurately. I would imagine we can apply a machine learning model to determine the optimum window for both, rather than employing trial and error.
