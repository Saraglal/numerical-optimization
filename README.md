# Numerical Optimization for ML

This repository contains Python implementations of various numerical optimization algorithms commonly used in machine learning. These algorithms are crucial for optimizing the parameters of machine learning models efficiently.

## Algorithms Included

1. **Batch Gradient Descent (BGD):** Traditional gradient descent where the parameters are updated using the gradients computed from the entire training dataset.

2. **Stochastic Gradient Descent (SGD):** Gradient descent where the parameters are updated using the gradients computed from a single randomly chosen sample from the training dataset.

3. **Mini-Batch Gradient Descent:** A compromise between BGD and SGD where the parameters are updated using the gradients computed from a small randomly chosen subset of the training dataset.

4. **Momentum-based Gradient Descent:** An extension of SGD that accumulates a velocity term to accelerate convergence and dampen oscillations.

5. **Nesterov Accelerated Gradient (NAG):** A modification of momentum-based gradient descent that incorporates lookahead updates for better convergence.

6. **Adagrad:** An adaptive learning rate optimization algorithm that scales the learning rate for each parameter based on the historical gradients.

7. **RMSProp:** Another adaptive learning rate optimization algorithm that scales the learning rate differently for each parameter based on the magnitude of recent gradients.

8. **ADAM:** A popular optimization algorithm that combines the ideas of momentum and adaptive learning rates.

9. **Second Order Optimization:** Optimization algorithms that utilize second-order derivatives (Hessian matrix) to approximate the curvature of the loss function for more precise updates. Examples include Newton's method and Quasi-Newton methods like BFGS.
