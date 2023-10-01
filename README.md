# Project title : Extracting-features-from-multi-goal-datasets

## I. Project introduction : 

People make generalization based on their diverse experiences in a specific environment. 

Thus, it is necessary to enable the models to leverage large offline task-agnostic datasets.

I want to design an unsupervised model and a supervised model that can extract useful features from these multi-goal dataset.

The unsupervised model will be used to generate ground truth labels, while the supervised model will be trained based on these generated labels. 

The objective is to make both the supervised model and unsupervised model succeed in learning and extracting meaningful features from the multi-goal datasets.


## II. Dataset description : 

I will use datasets collected from the Maze2D environments. The datasets is collected by a planner-based policy, and the overall dataset consists of 85000 trajectories collected from diverse goal settings.
For more detail, please check https://github.com/clvrai/spirl


Since the size of the dataset is too big to be uploaded in github, I will upload a google drive link to get access to the datasets :

https://drive.google.com/drive/folders/1H4qVcHJKD7voq2FGyXlE_wi8T7Qutpf0?usp=sharing


Explanatory variables : conc_images(local top-down view of a maze at timestep t), next_conc_images(local top-down view of a maze at timestep t+1), actions(action at timestep t)

Response variable : ylabel(corresponding state-action novelty)


Note the test dataset does not contain correct output (ground truth) values. 


## III. A baseline model : 

I will provide a baseline model that only uses state information to predict the state-action novelty.

This model shows whether states can extract useful features from the dataset by the guidance of state-action novelty.

The model is provided in the following link :
https://github.com/jack32666/Extracting-features-from-multi-goal-datasets/blob/main/maze_state_baseline_model.ipynb


## IV. Project proposal presentation video : 

https://drive.google.com/file/d/1AEf6J1BetDuv5eMzkKrzqsH3omult6QE/view?usp=sharing

