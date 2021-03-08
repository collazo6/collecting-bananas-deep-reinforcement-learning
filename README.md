# Deep Reinforcement Learning: Training Agents on Specified Tasks
## Introduction
Deep Reinforcement Learning is among the most promising breakthroughs when it comes to the future of deep learning and realizing *actual* artificial intelligence.  While more primitive algorithms may be used for simple prediction tasks, Reinforcement Learning algorithms such as Deep Q Networks enable scientists to train an agent on tasks through experience in predefined ecosystems.  This concept is very similar to the way humans are able to learn from their environment.  Through real-world experiences, humans are able to evaluate cues of encouragement or dissuasion from sensory information in order to build on their ideas on how to interact with the world around them.  Deliberate mathematical equations, theory and deep learning combine to enable this learning technique in artificial reality.

## Details
Utilizing a predefined environment, the above code initializes and trains an agent to perform a specific task through the use of positive and negative feedback.  Traversing a large square world, the agent selects actions based, in part, on optimizing its performance utilizing stored information on past experiences.

For this task, the agent is challenged with collecting as many `yellow` bananas :banana: as possible while avoiding `blue` bananas.  Each yellow banana collected will result in a score increase of `+1` while each blue banana will result in a decrease of `-1`.  The agent is able to choose from `4` discrete actions at each timestep: forward, backward, left or right.  Actions are selected either randomly (to allow the agent to explore alternative policies) or via predictions based on the agent's current state.  State information includes `37` continuous values that provide ray-based perception data of objects that lay in the forward direction.  These states are used as inputs of Deep Q Networks which are initialized and updated frequently based on past experiences and their respective outcomes in order to optimize the agent's behavior over time.
