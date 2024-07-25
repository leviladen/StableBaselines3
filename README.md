# StableBaselines3-with-Carla-Tutorial
This repo is a simple tutorial describing how to run an RL experiment with StableBaselines3. A few changes have been made to the files in this repository for it to be compatible with the current version of stable baselines 3. 
The files provided are courtesy of the Youtube channel 'Full Sim Driving'. 

The link to the video can be found here: https://www.youtube.com/watch?v=f31Mu5Yxc60&list=PLKtcx3w8WPyP7rxCHByn9pt66sT4hi3Jp.

The carenv.py and train.py files have been slightly altered to fit the current standards. 

### 1. Create a conda environment if you have not already done so. 

- https://docs.anaconda.com/miniconda/
- `conda create -n carla python=3.8`
- Keep in mind, this will require python 3.8 to run Carla properly
- Remember that you can always create a new environment if an old one has been messed up.


### 2. Activate your Conda Environment in the command line

- `conda activate [env_name]`


### 3. Install Stable Baselines 3 with the following command.

- `pip install stable-baselines3`


### 4. Install python packages Tensorflow and Open-CV.

- `pip install TensorFlow`
-  `pip install opencv-python`


### 5. Run Carla on your terminal at the port specified in carenv.py


