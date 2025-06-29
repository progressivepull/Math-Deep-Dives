# Math-Deep-Dives
Analysis in mathematics is a vast and intricate field that deals with the rigorous study of limits, continuity, differentiation, integration, sequences, series, and more. It builds the foundation for understanding calculus, real and complex functions, measure theory, and functional analysis. Some key concepts include:

* **Limits and Continuity:** Exploring how functions behave as inputs approach certain values.

* **Differentiation:** Understanding rates of change and slopes of curves.

* **Integration:** Accumulating quantities and finding areas under curves.

* **Sequences and Series:** Investigating infinite sums and convergence properties.

* **Measure Theory:** Formalizing the notions of length, area, and probability.

* **Functional Analysis:** Studying infinite-dimensional spaces and operators.

# Table of Context

* **[Dot Product](./dot_product.ipynb)** – or scalar product is an algebraic operation that takes two equal-length sequences of numbers (usually coordinate vectors), and returns a single number.
  - [Dot product - wikipedia](https://en.wikipedia.org/wiki/Dot_product)
  - [Can any one explain why dot product is used in neural network and what is the intitutive thought of dot product](https://stats.stackexchange.com/questions/291680/can-any-one-explain-why-dot-product-is-used-in-neural-network-and-what-is-the-in)
  - [The Dot Product — Topic 14 of Machine Learning Foundations - John Krohn - YouTube](https://www.youtube.com/watch?v=E5zLj5Mk28w)

$$a ⋅ b = |a| × |b| × \cos(θ)$$

  <img src="/images/dot_product/triangle1.png" alt="Triangle 1" width="500" height="500">

* **[Natural Exponential](./natural_exponential.ipynb)** – The natural exponential function, written as `e^x` or `exp(x)`, is a special type of exponential function that uses the constant `e ≈ 2.71828` as its base. It’s called "natural" because it arises organically across a wide variety of mathematical and scientific contexts—especially when modeling continuous growth or decay processes. This function plays a foundational role in calculus, differential equations, and probability theory.
  
$$
f(x) = e^x
$$

* **[Computes The Weighted Sum](./computes_the_weighted_sum.ipynb)** - the process of calculating the total (sum) of a set of values, each multiplied by a corresponding weight. This is commonly known as the weighted sum or weighted average.

    In simple terms:  
    Given values $x_1, x_2, \ldots, x_n$ with corresponding weights $w_1, w_2, \ldots, w_n$, the weighted sum is:

$$
\text{Weighted Sum} = x_1 \times w_1 + x_2 \times w_2 + \ldots + x_n \times w_n = \sum_{i=1}^n x_i w_i
$$

* **[Mean Squared Error Loss](mean_squared_error_loss.ipynb)** (MSE) - is a commonly used metric to measure the average of the squares of the errors between predicted values and actual values. It is widely used in regression analysis and machine learning to evaluate how well a model's predictions match the actual data.
  
$$
\text{MSE} = \frac{1}{n} \sum_{i=1}^{n} (y_i - \hat{y}_i)^2
$$ 

     [Mean Squared Error Loss-Square The Differences](mean_squared_error-square_the_differences.ipynb)

* **[Vector](vector.ipynb)** - A vector in math is a quantity that has both magnitude (length) and direction. It's a fundamental concept in geometry, physics, and engineering, and it's especially useful for describing movement, forces, and positions in space.
*  **[Sigmoid Function](sigmoid_function.ipynb)** - The sigmoid function is a mathematical function that maps any input value (real number) to a value between 0 and 1. It's widely used in fields like machine learning and statistics, particularly in logistic regression and neural networks.
  
$$\sigma(x) = \frac{1}{1 + e^{-x}}$$

* **[Sigmoid Derivative](sigmoid_derivative.ipynb)** - It has an elegant mathematical property. It connects the function back to itself—its slope depends on its value at a given point. This simplicity is one of the reasons sigmoid derivatives are popular in neural networks for activation gradients during backpropagation.

$$\sigma'(x) = \sigma(x) \cdot (1 - \sigma(x))$$

* **[Forward Pass](forward_pass.ipynb)** - In the context of neural networks, the forward pass is the process of passing input data through the network to generate an output. It’s the first phase of computation, where the model makes a prediction based on current weights and biases.