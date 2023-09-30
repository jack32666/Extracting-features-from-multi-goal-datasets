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


Since the size of the dataset is too big to be uploaded in github, I will upload google drive links to get access to the datasets :

https://drive.google.com/drive/folders/1H4qVcHJKD7voq2FGyXlE_wi8T7Qutpf0?usp=sharing
