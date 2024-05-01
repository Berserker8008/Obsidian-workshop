{{date:01052024}}{{time:1500}}
Status: #concept
Tags : [[AI]] [[Math]]
# Gradient Descent

## Definition:
Gradient descent is an [[optimization]] algorithm commonly used in [[machine learning]] and [[deep learning]] to minimize the cost function associated with a model. 

## The goal:
iteratively move towards the minimum of the [[loss|cost]] function by adjusting the model's parameters.

## How it works:
- **Initialization:** start with an initial set of [[parameter]] values. Random or based on prior knowledge
- **Compute the Cost Function** Calculate the [[gradient]] of the cost function with respect to each parameter. The gradient is a [[vector]] that points in the direction of the steepest increase of the cost function. In other words, it indicates the direction in which the parameters should be adjusted to.
- **Update Parameters** adjust the parameter in the opposite direction of the gradient. The size of the adjustment is determined by the [[learning rate]]
$$\theta = \theta - learning rate \times gradient$$
-  **repeat** until converge

## Variants of gradient descent:
- [[Stochastic Gradient Descent (SGD)]]
- [[Mini-batch Gradient Descent]]

## Direction:
- Gradient direction is the direction of maximum increase for a function
- Negative gradient is the direction of maximum decrease for a function

---
# References