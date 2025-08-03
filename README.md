### Solving the Schrödinger Equation via Physics-Informed Machine Learning

__Repository__: [SE-PINN](https://github.com/SE-PINN/SE-PINN)

__Summary__: The mathematical properties of __normality__, __symmetry__, and __orthogonality__ are integrated into a neural network in PyTorch via a __custom loss function__ and a __custom architectural layer__ so that its predictions satisfy these properties by design.

__Figure__: The prediction of the __energy eigenvector__ (left) appears to converge, but the prediction of the __energy eigenvalue__ (right) is slower. Visit the repository to see the same visualization when the model is constrained to respect __symmetry__ in its predictions.

![Animation of PINN](https://github.com/SE-PINN/SE-PINN/blob/main/assets/no_enforcement_of_symmetry.gif)
