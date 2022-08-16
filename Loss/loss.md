# Loss

## What is loss?

Loss is a number that represents how bad the model is.  
i.e.

- If the loss is low, the model is good.
- If the loss is high, the model is bad.

Our goal is to reduce the loss.

There are multiple ways to calculate loss, there is no one best way.

### Squared Loss (Commonly used)

The squared difference between the actual value and the predicted value is the loss.

Normally we don't need the loss of one example so we use the mean squared error across all our examples.

Mean Square error (MSE) is the average squared loss per example over the whole dataset. That is, it is the mean of the squared difference between the true value and the predicted value.
