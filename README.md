# mario-ml
This is my own version of trying to create an ML agent that will learn how to play Super Mario Bros

# IMPORTANT!!

Currently, specific version of Python and Retro Gym are needed to make this project run. 

You can use the `environment.yml` file to create an environment. By default the environment will be named `marioEnv`. Use the command `conda env create --file=environment.yml` in miniconda to have teh full environment created for you. For more information on managing environments with Conda, see their [documentaion here](https://conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html#activating-an-environment)

As of right now, you will still need to do `pip3 install gym_super_mario_bros`, `pip3 install stable_baselines3`, `conda install opencv`, `install shimmy` but I do plan to update the `environment.yml` so that wont need to happen. You can view the contents of the yml file to see if you need to install and I forget to update the README.

Python version 3.8.17 can be found on the [Python Downloads](https://www.python.org/downloads/) page.

Gym version 0.21.0 can be installed using `pip install gym==0.21.0`
