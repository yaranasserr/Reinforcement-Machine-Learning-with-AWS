# Reinforcement-Machine-Learning-with-AWS


https://user-images.githubusercontent.com/72654303/236627105-ee7b5eac-86d4-43d1-a496-e40616868035.mp4


AWS DeepRacer Reinforcement
Average reward
This graph represents the average reward the agent earns during a training iteration. The average is calculated by averaging the reward earned across all episodes in the training iteration. An episode begins at the starting line and ends when the agent completes one loop around the track or at the place the vehicle left the track or collided with an object. Toggle the switch to hide this data.
Average percentage completion (training)
The training graph represents the average percentage of the track completed by the agent in all training episodes in the current training. It shows the performance of the vehicle while experience is being gathered.
Average percentage completion (evaluation)
While the model is being updated, the performance of the existing model is evaluated. The evaluation graph line is the average percentage of the track completed by the agent in all episodes run during the evaluation period.
Best model line
This line allows you to see which of your model iterations had the highest average progress during the evaluation. The checkpoint for this iteration will be stored. A checkpoint is a snapshot of a model that is captured after each training (policy-updating) iteration.
Reward primary y-axis
This shows the reward earned during a training iteration. To read the exact value of a reward, hover your mouse over the data point on the graph.
Percentage track completion secondary y-axis
This shows you the percentage of the track the agent completed during a training iteration.
Iteration x-axis
This shows the number of iterations completed during your training job.

<img width="302" alt="image" src="https://user-images.githubusercontent.com/72654303/236625773-0df84c96-5c14-4693-aa5b-7485620f1acf.png">
<img width="669" alt="image" src="https://user-images.githubusercontent.com/72654303/236625801-45f5d482-628e-4e80-8cba-d6a20585b340.png">
