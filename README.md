# dpickleball-xiamen-202604-project
This project focused on training an autonomous dPickleBall agent using  reinforcement learning (https://github.com/dPickleball/dPickleBallEnv).

The training pipeline was divided into two stages. 
1. First, *Foundation Wall* Training was used as a warm-up environment so that the agent could learn basic paddle control, ball chasing, hitting, recovery, and stronger returns through a six-level curriculum.
2. Second, *League Self-Play* Training was conducted in the real Unity dPickleBall 
environment. In this stage, the member-contributed agents were collected into an 
opponent pool containing weak, medium, and strong policies. The six selected learner 
agents were then trained against the opponent pool, which helped the agents become 
more robust against diverse opponent styles.
