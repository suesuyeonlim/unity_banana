# Udacity - Deep Reinforcement Learning Nanodegree (Navigation)


## Project Description
This project involves working with the Banana environment. In this environment, an agent navigates and collect bananas in a large, square world.

A reward of +1 is provided for collecting a yellow banana, and a reward of -1 is provided for collecting a blue banana. Thus, the goal of your agent is to collect as many yellow bananas as possible while avoiding blue bananas.

The state space has 37 dimensions and contains the agent's velocity, along with ray-based perception of objects around the agent's forward direction. Given this information, the agent has to learn how to best select actions.

Untrained

![Alt Text](https://media.giphy.com/media/paJEEd7bCXdDK7ebcB/giphy.gif)

Trained

![Alt Text](https://media.giphy.com/media/ttdcNRnXx8XZJSywmu/giphy.gif)

The assignment is to train agents to get an average score of 0.5 over 100 consecutive episodes.


## Python Environment Set-Up
To set up your python environment to run the code in this repository, follow the instructions below.

1. Download and install [Anaconda](https://www.anaconda.com/download/), if you don't already have it.

2. Create (and activate) a new environment with Python 3.6.

- Linux or Mac:
  ```
  conda create --name drlnd python=3.6
  conda activate drlnd
  ```
- Windows:
  ```
  conda create --name drlnd python=3.6 
  activate drlnd
  ```

3. Clone the repository and navigate to the root folder.
  
  ```
  git clone https://github.com/suesuyeonlim/unity_tennis.git
  cd unity_tennis
  ```

## Requirements to Run the Code in Repository
In order to prepare the environment, follow the next steps after downloading this repository:

1. Download the environment from one of the links below. You need only select the environment that matches your operating system:

  - Linux: click [here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux.zip)
  - Mac OSX: click [here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana.app.zip)
  - Windows (32-bit): click [here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86.zip)
  - Windows (64-bit): click [here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86_64.zip)
  
Place the file in the unity_banana/banana_apps/ folder, and unzip (or decompress) the file(s).

2. To install the mlagents Python package, run from the command line:
  
  ```
  python -m pip install mlagents==0.28.0
  ```
3. Install the following packages:
  
  - Numpy
  - Torch
  - Random
  - Copy
  - Collections

4. Run the following command:

  ```
  $ jupyter notebook
  ```
  
  This will open the Jupyter Notebook software and notebook in your browser which you can use to explore and reproduce the experiments that have been run.

## Code and Resources
- Report.ipynb: A document that describes the results, details of the implementation, and future ideas.
- checkpoint: A folder that contains saved weights from the programs below.
- Navigation_vanilla.ipynb
- Navigation_rainbow_wo_per.ipynb
- Navigation_rainbow_wo_per_distributional.ipynb