Rough process... GPT supplied

- Input Phase: You supply the MLP with a set of inputs (features) that represent your data.
- Forward Pass: The inputs are passed through the layers of the MLP, where each neuron applies its weights, biases, and activation functions. This process transforms the inputs step by step until you reach the final output layer.
- Output Phase: The MLP produces outputs (predictions) based on the input data.
- Loss Calculation: The outputs from the MLP are then compared to the desired outputs (targets) using the loss function. The loss function quantifies how well the predictions match the targets.
- Training Cycle: The loss value indicates how far off the predictions are, and this information is used to adjust the model's parameters (weights and biases) through backpropagation in order to minimize the loss in future iterations.

Training:
- Forward Pass is what calculates our output and predictions at the end of the MLP...
- We use our loss function to calculate the initial gradient before we backpropagate...
- And then, we backpropagate the gradients back until we reach the beginning
- And we do this again, and again, adjusting our learning rates etc, until we're happy with the predictions.

