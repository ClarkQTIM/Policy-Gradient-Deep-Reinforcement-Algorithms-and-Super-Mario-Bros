# Policy-Gradient-Deep-Reinforcement-Algorithms-and-Super-Mario-Bros
Currently in progress.

This project is an exploration of the mathematical and programming foundations of several policy gradient deep reinforcement learning algorithms applied to OpenAI Gym's Super Mario Bros. Policy Gradient algorithms in Reinforcement Learning are those which seek to find the best policy, $\pi$, to maximize:

$J(\mathbf{\theta}) = \mathbf{E}_{\tau \sim p_{\mathbf{\theta}}(\tau) \left[ \sum_{t=1}^{T} \gamma^{t-1} r_{t+1} \right] $
