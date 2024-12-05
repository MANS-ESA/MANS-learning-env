to clone this repo with the ml-agents submodule do : 
 - git clone --recurse-submodules https://github.com/MANS-ESA/MANS-learning-env.git

to install ml-agents 
You must have python 3.10.10
then do : 
 - pip install -e  MANS-ml-agents/ml-agents-envs
 - pip install -e  MANS-ml-agents/ml-agents

then your package are inside the MANS-ml-agents folder

use ./config folder to change the hyperparameters of the training and model parameters

to start learning do : 
 - mlagents-learn ./config/myfile.yaml --run-id=myId

to resume a train use option --resume

