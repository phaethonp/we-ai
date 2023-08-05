# Decision-Making Machines
Components<br>

### Neural Ordinary Differential Equations (ODEs)
A differential equation is parameterized by neural networks, allowing us to learn complex, continuous-time dynamics from data<br><br>

* **Differential Equation:** a differential equation describes how a quantity changes over time or space.<br><br>
* **Parameterized by Neural Networks:** In the context of Neural ODEs, the differential equation is not defined with fixed mathematical functions. > > > Instead, the functions that describe the rate of change are represented by neural networks. The weights and biases of these neural networks are the parameters that need to be learned from the data.<br><br>
* **Learn Complex, Continuous-Time Dynamics:** By using neural networks to represent the differential equation, we can capture complex relationships and patterns in the data.<br> Since the differential equation describes continuous-time dynamics, the model can represent how the system evolves smoothly over time without needing equations, discrete steps, or layers.<br><br>
* **From Data:** Like other machine learning models, Neural ODEs are trained on data. By adjusting the parameters of the neural networks (i.e., the weights and biases), the model learns to accurately represent the underlying dynamics of the data.

# Applications
###  Modelling City Growth: Dynamic Urban Development
Lets say we want to create a model for the growth and urban development of a city.<br>
We could start as follows:<br>
* **Population Growth**
Imagine we have data that represents the population of a city over time, and we want to model how the population changes. A traditional approach might involve fitting a specific mathematical model to the data, such as a logistic growth model.<br><br>

With Neural ODEs, instead of choosing a specific mathematical model, we would define a differential equation where the **rate of change** of the **population** is represented by a **neural network**. We would then use data about the population over time to train the neural network, adjusting its weights and biases so that the differential equation accurately models the observed population dynamics.<br><br>

The result is a flexible and powerful model that can capture complex, continuous-time behavior, without being restricted to a specific mathematical form.<br>It can be applied to a wide range of problems where understanding the continuous evolution of a system over time is essential.<br><br>

* **Urban Development:**
