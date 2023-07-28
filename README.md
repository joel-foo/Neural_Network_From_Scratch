# Neural network from scratch 
The only dependency required is NumPy.
- Support for the following is provided
   - Forward pass and backprop
   -  Batch and mini-batch gradient descent
   - Activation functions - sigmoid, relu, tanh, linear, softmax
   - Loss functions - MSE, binary cross entropy, cross entropy

+ Creating and training a model is simple (somewhat similar to the Tensorflow API):
   1. Create a list of `Layer` objects 
   2. Pass the created list and necessary parameters to instantiate the `NN` object
   3. Call `train` on the NN object
 
- Benchmarked using the MINST dataset
  - Simple network with a single hidden layer achieved 88% accuracy on the test set
