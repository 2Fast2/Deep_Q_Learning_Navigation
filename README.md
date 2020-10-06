# Deep Q-Learning Navigation
Deep Q-Learning agent for final project of Udacity Nanodegree Program.


## Project Details
This project consist in train an agent and navigate in a large but finite square to pick yellow bananas, while avoiding blue bananas.

### Goal
A reward of `+1` is provided for collecting a **yellow** banana, and a reward of `-1` is provided for collecting a **blue** banana. Thus, the goal of your agent is to collect as many yellow bananas as possible while avoiding blue bananas.

Like the task is episodic, and in order to solve the environment, the agent must get an average score of +13 over 100 consecutive episodes.

### Environment
The state space has 37 dimensions and contains the agent's velocity, along with ray-based perception of objects around the agent's forward direction. Given this information, the agent has to learn how to best select actions. Four discrete actions are available, corresponding to:

- `0` - move forward.
- `1` - move backward.
- `2` - turn left.
- `3` - turn right.

```
Unity brain name: BananaBrain
        Number of Visual Observations (per agent): 0
        Vector Observation space type: continuous
        Vector Observation space size (per agent): 37
        Number of stacked Vector Observation: 1
        Vector Action space type: discrete
        Vector Action space size (per agent): 4
        Vector Action descriptions: , , , 
```

## Getting Started
* **Step 1, ensure the fulfilment of environment requirements.**
    * Python 3.6 or higher.
    * If you wnat to create an environment to isolate the environment, you can install [miniconda3](https://docs.conda.io/en/latest/miniconda.html).
    * Install [git](https://git-scm.com/downloads) to clone the repository. (This is an optional step)
    
* **Step 2, download the Unity Environment.**
  
  You need only select the environment that matches your operating system:

    * Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux.zip).
    * Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana.app.zip).
    * Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86.zip).
    * Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86_64.zip).
    
  Then, place the file in the `p1_navigation/` folder in the DRLND GitHub repository, and unzip (or decompress) the file.

* **Step 3, clone or download the code.**

  You can clone the code from the git repository
  
  ```
  git clone https://github.com/2Fast2/Deep_Q_Learning_Navigation.git
  ```

  or download as a zip file.

* **Step 4, install necessary dependencies.**
  
  Install other necessary libraries from the `requirements.txt` file.
  
  ```
  pip install -r requirements.txt
  ```
## Instructions
