# Udacity Deep Reinforcement Learning: Project 2, Continuous Control  

## Environment 
* Reacher Environment 
* The goal of this problem is for the agent (a double jointed arm) to track a goal location, where it gives a reward of +0.1 for each timestep the hand is in the goal location 
* For the purposes of this project, the environment is considered solved when the agent achieves an average score (accumulated reward over an episode) of +30.0 over 100 episodes. 

## State Space: 
* 33-Dimensional continuous observation space, (includes agent position, orientation and there respective velocities) 

## Action Space: 
* 4-Dimensional continuous space (torque applied to two joints), with each element bounded to be within (-1,1) 

## Installation and Usage 
* This notebook can be used by simply opening it in the provided Udacity Project Workspace 
* Alternatively, you can run this locally: 
    1. Clone this repository
    2. To get the python/conda environment setup, follow these instructions: https://github.com/udacity/deep-reinforcement-learning#dependencies
    3. Make sure you have jupyter properly installed, and you may have to get an archived version of pytorch 
    4. Download the environment for Linux: https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one\_agent/Reacher\_Linux.zip 
    5. In the repository directoy root `mv <path/to/Reacher_Linux.zip\> .`
    6. Then run `conda activate drlnd` 
    7. In your local directory, to see the trained agent in action: `python main.py "./Reacher\_Linux/Reacher.x86\_64"` 
    9. To train the agent yourself, use the ipynb notebook and use the Udacity Project Workspace as stated above so that you can take advantage of the GPU, hit "run all cells" 

