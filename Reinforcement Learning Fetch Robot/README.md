# CSC591 The Robot Gym


**Description** -
1. Implemented the Reinforcement learning on Fetch Robotic arm, training it to reach an 3D object in it configuration space using Open AI Gym & MuJoCo Simulator.
2. Deep Deterministic Policy Gradient (DDPG) algorithm was deployed to estimate the next state of the robotic arm in on a continuous action space.
3. Actor Critic models were developed using PyTorch.
4. Hindsight Experience Replay was added to the DDPG to increase the effectiveness and reduce the learning time for the robot.
5. Successfully reproduced the results of Google Deepmind on their implementation of DDPG & DDPG+HER.

**Results** -
<p float="left">
  <img src="https://user-images.githubusercontent.com/25856691/99007206-bf5ac200-2511-11eb-8f98-b0c3084dba11.png" width="500" height="400"/>
  <img src="https://user-images.githubusercontent.com/25856691/99007213-c2ee4900-2511-11eb-8caa-5d574909cf73.png" width="500" height="400"/>
</p>


**Implementation & Usage** -
1. notebooks directory contains our implementation of the DDPG & DDPG+HER code in PyTorch along with beginners notebook for OpenAI Gym.
2. Install [OpenAI Gym](https://github.com/openai/gym), MuJoCo Simulator for the deployment.
3. python directory contains reference baseline DDPG & DDPG+HER model in TensorFlow API.
4. Here is the [paper](https://github.com/vivekrathi14/CSC591-The-Robot-Gym/files/5796974/The_Robot_Gym.pdf) that was submitted in class.








