# Crawler robot
The **crawler robot** is a simple and low-cost physical platform for the initial study of [reinforcement learning](https://en.wikipedia.org/wiki/Reinforcement_learning) algorithms. It consists of a 2 DoF plannar arm actuated by servomotors mounted on a mobile base with 2 free wheels .<br>

![crawler](https://user-images.githubusercontent.com/107052856/199168370-a2930d46-5c04-4585-90a6-cc77716fefe0.jpeg)
 <br>
The reinforcement learning algorithm used for the robot to find a sequence of actions that provide locomotion by its own is known as [**Q-learning**](https://es.wikipedia.org/wiki/Q-learning). The agent starts by executing random movements with his arm and when some sequence manages to mobilize the platform, the robot receives a positive reward. It is the repetition of this reward process that allows the robot to strengthen the movements that give it consistent movement and ignore the ones that do not.

![policy](https://user-images.githubusercontent.com/107052856/199168945-4ae1d700-5b0c-4bb4-9215-6672626eb882.gif)


# Tools and materials
- Ardunio Uno board
- Matlab 2018
- 2 hobby servomotors
- Optical enconder 
- Bluetooth module
 
 # Demo
- The robotic agent [performing random movements](https://www.youtube.com/watch?v=am49DNG4l4M&list=PLQBwkbxMqU0CwwgrcaWHP4ouFjho0Iy4H&index=5) in order to learn an **optimal policy** through negative feedback.
- The robotic agent [executing a locomotion strategy](https://www.youtube.com/watch?v=am49DNG4l4M&list=PLQBwkbxMqU0CwwgrcaWHP4ouFjho0Iy4H&index=5) through a set of self-learned coherent movements
