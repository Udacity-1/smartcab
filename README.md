# Machine Learning Engineer Nanodegree
## Reinforcement Learning
## Project: Training a smartcab to drive


**Brief description**

Construct an optimized Q-Learning driving agent that will navigate a Smartcab through its environment towards a goal.
A driving agent that gets the Smartcab to its destination while running red lights or narrowly avoiding accidents would be considered 
unsafe. Similarly, a driving agent that frequently fails to reach the destination in time would be considered unreliable. Maximizing the
driving agent's safety and reliability is the aim of this project.

The following idea will be present behind the solution:
For every state the agent visits, create an entry in the Q-table for all state-action pairs available. Then, when the agent encounters a
state and performs an action, update the Q-value associated with that state-action pair based on the reward received and the interative
update rule implemented. 
