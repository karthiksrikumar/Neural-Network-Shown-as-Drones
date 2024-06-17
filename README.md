# Neural Network Drone Simulator

This project showcases the implementation of a neural network that controls the movement and behavior of simulated drones. The neural network's goal is to guide the drones towards a target destination, represented by a red marker on the screen. The drones' movements and decision-making processes are entirely driven by the neural network, providing an interactive and visual representation of how these powerful machine learning models operate.

## Neural Network Architecture

The neural network in this project is implemented using JavaScript and consists of the following components:

1. **Input Layer**: The input layer receives various data points that describe the current state of the drone, such as its position, velocity, and distance from the target.

2. **Hidden Layers**: The neural network has multiple hidden layers, each containing a configurable number of neurons. These hidden layers process the input data and perform complex computations to determine the appropriate actions for the drone.

3. **Output Layer**: The output layer produces the final decisions or actions for the drone, such as adjusting its velocity, direction, or other movement parameters.

The number of neurons in each layer, as well as the number of hidden layers, can be customized to suit different problem complexities and accuracy requirements.

## Neural Network Training

Before the neural network can control the drones effectively, it must undergo a training process. This involves exposing the neural network to a large dataset of scenarios, where the desired output (drone actions) is known. The neural network adjusts its internal weights and biases iteratively, minimizing the difference between its predicted output and the desired output.

During the training process, the neural network learns to recognize patterns and relationships between the input data (drone state) and the desired output (actions to reach the target). This process is facilitated by various techniques, such as backpropagation and optimization algorithms like stochastic gradient descent.

## Drone Visualization

To make the neural network's decision-making process more tangible and engaging, we've created a visual representation using simulated drones. These drones navigate through a virtual environment, attempting to reach the red target marker.

The drones' movements are smooth and realistic, allowing you to observe the neural network's decisions in real-time. As the neural network processes the input data, you'll see the drones adjusting their trajectories, avoiding obstacles, and making strategic maneuvers to reach the target.

This visual representation not only makes the neural network's inner workings more accessible but also serves as a powerful tool for debugging, testing, and evaluating the model's performance in different scenarios.

## Neural Network Configurations

The project includes several pre-trained neural network configurations, each showcasing different behaviors and strategies for reaching the target. These configurations can be loaded and explored, providing insights into how the neural network's architecture and training process influence the drones' movements and decision-making abilities.

You can experiment with various configurations, observe how the drones respond to different environments and obstacles, and even modify the code to create your own custom neural network configurations.

