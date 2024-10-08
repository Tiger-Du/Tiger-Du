### Solving the Schrödinger Equation via Physics-Informed Machine Learning

__Repository__: [SE-PINN](https://github.com/Tiger-Du/SE-PINN)

__Summary__: The mathematical properties of __normality__, __symmetry__, and __orthogonality__ are integrated into a neural network itself via a __custom loss function__ and a __custom architectural layer__ in PyTorch so that its predictions respect these properties by design.

__Graphic__: This is an animation of how the __predictions__ of a model change as it is __trained__. Visit the repository to view the same animation for a less naive model that respects exact symmetry.

![Animation of PINN](https://github.com/Tiger-Du/SE-PINN/blob/main/assets/no_enforcement_of_symmetry.gif)
