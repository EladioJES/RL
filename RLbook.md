# Elements of Reinforcement Learning

1. Agent
2. Environment
3. Policy
4. Reward Signal
5. Value Function
6. **Model** of the environment, _optionally_
</br></br></br>
## Policy
> Roughly speaking, a policy is a mapping from perceived states of the environment to actions to be taken
when in those states. The policy is the core of a reinforcement learning agent in the sense that it alone is sufficient to determine behaviour.
</br>
## Reward signal
>It's a number sent from the environment to the reinforcement learning agent on each time step. The agent's sole objetive is to maximize the total reward it receives over the long run. The reward signal defines what are the good and bad events for the agent.
</br>
## Value function
>The value of a state is the total amount of reward an agent can expect to accumulate over the future, starting from that state. A value function specifies what is good in the long run.

Rewards are given by the environment at every time step, but values must be estimated and re-estimated over from sequences of observations an agent makes over a lifetime.

## Model
[State and action] &rarr; [Model] &rarr; prediction of next state and next reward
> Models are used for planning: deciding on a course of action by considering possible future outcomes before they are actually experienced.

There are **model-based** methods, as opposed to **model-free** methods that are explicitly trial-and-error learners. These are viewed as the opposite of planning.