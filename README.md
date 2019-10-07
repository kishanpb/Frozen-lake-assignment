# Frozen-lake-assignment
Texas A&amp;M Spring 2019 Artificial Intelligence assignment

# Introduction to the Frozen Lake problem:

The Frozen Lake environment is a 4×4 grid which contains four possible areas  — Safe (S), Frozen (F), Hole (H) and Goal (G). The agent moves around the grid until it reaches the goal or the hole. If it falls into the hole, it has to start from the beginning and is rewarded 0. The process continues until it learns from every mistake and reaches the goal eventually. Here is visual description of the Frozen Lake grid (4×4):

![alt text](https://analyticsindiamag.com/wp-content/uploads/2018/03/Frozen-Lake.png)

The agent in the environment has four possible moves — Up, Down, Left and Right. This assignment lets you implement Reinforcement Learning techniques like, Value Iteration, Policy Iteration, and Q-Learning. This environment will allow the agent to move accordingly. We are going to focus on non-slippery version of this environment (slippery version is where, with some small probability there's a chance that the agent takes a different action compared to the prescribed one!)

This grid has 16 possible blocks where the agent will be at a given time. At the current state, the agent will have four possibilities of deciding the next state. From the current state, the agent can move in four directions as mentioned which gives us a total of 16×4 possibilities. 

For more: Interested folks can look into https://github.com/openai/gym/blob/master/gym/envs/toy_text/frozen_lake.py of how Gym creates this environment(and to get an idea of what's the Frozen lake is all about!)

Source: https://www.analyticsindiamag.com/openai-gym-frozen-lake-beginners-guide-reinforcement-learning/

# Instructions for the assignment:

(Steps 1 to 2 is related to the setup, installation, etc)

1) Ensure you are using Python 3.5+ (for Gym) and have the following libraries/dependencies:
time, seaborn, matplotlib.pyplot, numpy, math, random

2) Refer https://gym.openai.com/docs/#installation for installing gym environment

a) People working with Windows OS can find solace using Anaconda (https://www.datacamp.com/community/tutorials/installing-anaconda-windows), and then installing Gym within Anaconda (https://anaconda.org/akode/gym).

b) People working with Mac OS or any Linux OS have an inbuilt python at their disposal. So, just follow the installation procedure given in openai website.

3) To know about Jupyter notebook, refer to https://jupyter-notebook-beginner-guide.readthedocs.io/en/latest/; one can use Anaconda (https://docs.anaconda.com/anaconda/install/) to use Jupyter notebook, and edit those base codes provided.

4) Clone this repository, and work with the local copy.

5) Use the base code for getting to know about gym parameters and obtaining the results. **Note:** The provided base code is for Policy Iteration part of the assignment, please feel free to use this for Value Iteration and Q-learning as well making obvious changes. Feel free to rearrange the base code as it suits you as a coder! 

6) Submit your local copy folder as a "FirstName-LastName.zip" in eCampus which will be made available later. **Note:** After you update the code(and get the results) in .ipynb files, save them as .html format and include these in the submission compressed folder("FirstName-LastName.zip").
