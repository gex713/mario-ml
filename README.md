# mario-ml
This is my own version of trying to create an ML agent that will learn how to play Super Mario Bros

# IMPORTANT!!

Currently, specific version of Python and Retro Gym are needed to make this project run. 

You can use the `environment.yml` file to create an environment. By default the environment will be named `marioEnv`. Use the command `conda env create --file=environment.yml` in miniconda to have the full environment created for you. For more information on managing environments with Conda, see their [documentation here](https://conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html#activating-an-environment)

As of right now, you will still need to do `pip3 install gym_super_mario_bros`, `pip3 install stable_baselines3`, `conda install opencv`, `install shimmy` but I do plan to update the `environment.yml` so that wont need to happen. 

Alternatively, you can use the `mario.yml` that is included to create an environment called `marioEnv-V2` which will have everything you need to train the model. However, for some reason, this breaks matplotlib so you wont be able to see an graphics generated in in plots. This does not affect the running or training in any way so if you dont care about looking at the grayscale or framestacking, create an environment from teh `mario.yml`.

Python version 3.8.17 can be found on the [Python Downloads](https://www.python.org/downloads/) page.

Gym version 0.21.0 can be installed using `pip install gym==0.21.0`
