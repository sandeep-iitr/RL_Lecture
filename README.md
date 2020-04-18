# RL_Lecture_Fall_2019
## Code used for course: CS M213A / ECE M202A

# 1. Environment Setup

```
1. Install the conda by following the instructions:
https://docs.conda.io/projects/conda/en/latest/user-guide/install/

2. Setup the environment

$conda create -n rlenv python=3.5 

$conda activate rlenv

$pip install jupyter

$pip install gym

$pip install tensorflow==1.14.0

$pip install keras==2.2.0

$pip install keras-rl

```


# 2. Running Examples
```
Activate the environment first:

$git clone https://github.com/nesl/RL_Lecture_Fall_2019.git

$cd RL_Lecture_Fall_2019

$conda activate rlenv

Now, the examples and the code files can be interactively executed using the jupyter notebook.

$jupyter notebook

```

# 3. Deleting the Environment
```
conda remove --name rlenv --all
```

