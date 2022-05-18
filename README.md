# Usage:

Running the jupyter notebook file ET_CarGoal_Context[r_e=1].ipynb can reproduce our results on the CarGoal environment, with the ending cost = 1.

In the default setting, we call the TD3_Context.py model as the learning algorithm, other ablation studies can be reproduced by replacing the algorithm with 
- TD3: reproduce on the ablation of using context models
- TD3_Context_Large: on the study of number of hidden parameters
- TD3_Context_Share: on the study of model structure
