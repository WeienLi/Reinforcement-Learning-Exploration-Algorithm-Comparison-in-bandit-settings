# Reinforcement-Learning-Exploration-Algorithm-Comparison-in-bandit-settings
The purpose of this expriment is to compare different exploration algorithm with different hyperparameters in stochastic and non-stochastic settings in 
the bandit expriment. We start the expriment by comparing how different learning rates (aka. Alpha) affects the learning (how long it takes to converge to
the true probability). Then using the exploration algorithms including Epsilon Greedy, Upper Confidence Bound and Thompson Sampling algorithm with 
different parameters setting to obtain the reward, fractions of optimal arm chosen, regret and cumulative regret for 100 runs with 1000 timestamp. Last
we decide to measure how much the best hyperparameters settings in each algorithm are prone to changes in stochastic enviroment by changing the probability
at the 500 time stamp. 
