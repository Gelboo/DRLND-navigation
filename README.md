# DRLND-navigation
Banana_Navigation (picking Yellow, avoid Blue)

# objective of the environment
To train an agnet to be able to collect ** yellow banana ** & avoiding ** blue banana **

# Enviornment 
The environment created with Unity, and we are going to use python-api to interact with the environment [unityagents](https://pypi.org/project/unityagents)

## State
The input to the model is images consist of 37 dimensions and contain the agent's velocity, along with ray-base perception of objects around the agnet's forward direction

## Action
the agent can pick an action from 4
* ```0``` - move forward
* ```1``` - move right
* ```2``` - turn left
* ```3``` - turn right

## Rewards
* ```+1``` for collecting yellow banana
* ```-1``` for collecting blue banana

## Defination of solve
when the agent get an average score of +13 over 100 consecutive episodes

## How to run the code
You could use the [insturction in the DRLND GitHub repository](https://github.com/udacity/deep-reinforcement-learning#dependencies) to setup the Deep-Reinforcement-Leanring environment 

Which highlighting these steps
1. create a conda virenv ``` conda create -n drlnd python=3.6```
2. cd to the downloaded repo ``` cd /Download_path/DRLND-naviigation ``` ** 'Download_path' ** the location where you download the repo
3. activate the conda environment ``` conda activate drlnd ```
4. install the packages ``` pip install . ```
5. create IPython kernel ``` python -m ipykernel install --user --name drlnd --display-name "drlnd" ``` 
6. open jupyter-notebook in the root-directory and open Navigation.ipynb ``` jupyter notebook Navigation.ipynb ```
7. Execute the secions in the notebook
