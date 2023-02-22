# AWS-DeepRacer-using-reinforcement-learning-RL-
We will train a reinforcement learning (RL) model and see a simulation of how that model performs on a track.

## Before you start
In this tutorial, you will train a reinforcement learning (RL) model and see a simulation of how that model performs on a track. The AWS DeepRacer Student League is where you compete for the fastest lap times with you friends. You have the option to opt out of submitting your trained model to the Student League.

## How is an RL model trained?
In AWS DeepRacer, an agent (car) learns from an environment (track) by interacting with it. During training, the model iterates and updates different parameters based on rewards received.

## Model training is an iterative process
Training a model is like creating a prototype. Each model iteration is a step towards finding the optimal parameters. When training has finished, clone your model to continue improving it.

## Improving your model
After training an initial model, you can use the current state of the model's parameters as the starting point for the next model by choosing clone model. Submit to the leaderboard to evaluate your model's performance. Look for the race time and the number of times your car went off track.

## Now Choose a Track.
![](https://raw.githubusercontent.com/BhaskarKulshrestha/AWS-DeepRacer-using-reinforcement-learning-RL-/main/images/Screenshot%202023-02-23%20001219.png?token=GHSAT0AAAAAAB452XSSMD2AXJ3EGEISUX6UY7WOXKA)

## Now Choose a Algorithm

A model training algorithm is a procedure that uses data to create a model. These algorithms maximize total reward differently. Proximal Policy Optimization (PPO) explores the environment less compared to Soft Actor Critic (SAC).

## Now choose a reward function and coustomize it.

#### What is a reward function?
The reward function is Python code that describes immediate feedback in the form of a reward or penalty to move from a given position on the track to a new position.

#### What is the purpose of a reward function?
The reward function encourages the vehicle to make moves along the track quickly to reach its destination.

![](https://raw.githubusercontent.com/BhaskarKulshrestha/AWS-DeepRacer-using-reinforcement-learning-RL-/main/images/Screenshot%202023-02-23%20001635.png?token=GHSAT0AAAAAAB452XSSJXNAQKLJL5WLDX22Y7WOY4Q)

<strong>Here we choose option 2.</strong>

### Now choose the training Duration (Choose atleat 10 min).
### Give some model description.

<i>You have successfully crafted a reward function and are now ready to train the model.</i>

### Now click on train model .

## A gilmpse of End Result
![](https://raw.githubusercontent.com/BhaskarKulshrestha/AWS-DeepRacer-using-reinforcement-learning-RL-/main/images/Screenshot%202023-02-23%20010438.png?token=GHSAT0AAAAAAB452XSTWAZWHMWHUULZZWMEY7WPTSA)
