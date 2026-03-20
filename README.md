# ML Journey - Week 1: Linear Algebra

## What I learned
- Vectors and matrices
- Matrix multiplication and dot products
- Transpose and identity matrix
- Loading images as NumPy matrices
- Brightness adjustment using scalar multiplication

## Projects built
- NumPy matrix operations
- Image brightness adjuster (grayscale + colour)

## Key insight
An image is just a matrix of numbers. Multiplying by 1.5 makes it brighter. Multiplying by 0.5 makes it darker. That's it.

## GitHub
All code pushed daily to this repo.
                                     


## Week 2: Calculus for ML

### What I learned
- What a derivative is — rate of change of a function
- Power rule for derivatives — f(x) = xⁿ → f'(x) = n × xⁿ⁻¹
- Partial derivatives — how a function changes when only one variable moves
- Gradient — direction of steepest uphill at any point
- Gradient descent — moving opposite to gradient to find minimum error
- Learning rate — controls how big each step is in gradient descent

### Projects built
- Derivative visualiser — plotted f(x) = x² and its derivative f'(x) = 2x
- Gradient visualiser — 3D bowl + gradient arrows showing direction
- Gradient descent 1D — x² minimised from scratch in 20 steps
- Gradient descent 2D — f(x,y) = x² + y² minimised with both variables
- 3D descent path — gradient descent sliding down a 3D surface visually
- Learning rate comparison — 0.001, 0.01, 0.1, 0.5 compared on one graph

### Key insight
Gradient descent is just one formula: x = x - learning_rate × gradient
That one line is how every neural network in the world learns.
Netflix, ChatGPT, Google Photos — all use this exact formula millions of times.

### GitHub
All code pushed daily to this repo.
