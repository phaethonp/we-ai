# Decision-Making Machines
Components<br>

### Neural Ordinary Differential Equations (ODEs)
A differential equation is parameterized by neural networks, allowing us to learn complex, continuous-time dynamics from data<br><br>

* **Differential Equation:** a differential equation describes how a quantity changes over time or space.<br><br>
* **Parameterized by Neural Networks:** In the context of Neural ODEs, the differential equation is not defined with fixed mathematical functions. > > > Instead, the functions that describe the rate of change are represented by neural networks. The weights and biases of these neural networks are the parameters that need to be learned from the data.<br><br>
* **Learn Complex, Continuous-Time Dynamics:** By using neural networks to represent the differential equation, we can capture complex relationships and patterns in the data.<br> Since the differential equation describes continuous-time dynamics, the model can represent how the system evolves smoothly over time without needing equations, discrete steps, or layers.<br><br>
* **From Data:** Like other machine learning models, Neural ODEs are trained on data. By adjusting the parameters of the neural networks (i.e., the weights and biases), the model learns to accurately represent the underlying dynamics of the data.
