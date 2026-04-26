# CS370
SNHU CS370 Submission

## Briefly explain the work that you did on this project: What code were you given? What code did you create yourself?
Code Given: I was provided with the TreasureMaze.py environment and the base ExperienceReplay.py class. This included the game logic for the grid (walls, treasure, and pits) and the memory buffer used to store the agent’s past experiences.
Code Created: I designed the Neural Network architecture (DQN) and the qtrain loop. This required implementing the Epsilon-Greedy logic to handle exploration and exploitation, the Bellman Equation to update Q-values, and the decay function to transition the agent from random movement to goal-oriented navigation. I also handled the integration between the environment's state and the model's predictions.

## Connect your learning from throughout this course to the larger field of computer science: What do computer scientists do and why does it matter? How do I approach a problem as a computer scientist?

Computer scientists are architechs that design with efficiency in mind. They look at code more than they write it and think, "hm, what could be done better?" It might involve changing scripts to functions, changing functions to algorithms or changing algorithms to reinforced learning. They don't just "write code"; they solve problems by translating abstract human needs into logical, repeatable processes.

To approach a problem as a computer scientist is to embrace Decomposition and Abstraction. Instead of looking at the treasure hunt as a big task, I had to break it down into the current state, the reward, and iteration. Instead of thinking of it as completing the goal, as long as the individual step was iterative enough it would take me to the goal. Even if a journey begins with a single step, it can take millions of them. Then I designed a transition from one system of action to another -- from random exploration to greedy exploitation of knowledge learned over multiple episodes.

Why it matters: In the larger field, this matters because it allows us to scale solutions. When the first step of a process is just as useful as the last step, you're not making a specific solution for a specific instance, you're making shoes for making the journey, wherever it may take you. It's an encapsulation and ideal of a perfect solution.


## What are my ethical responsibilities to the end user and the organization?
A computer scientist has a lot of ethical responsibilities to multiple entities. To their organization and the end-user. For the organization, it needs to be efficient, maintainable, cost-effective, and doesn't put them into a legal liability. Time and budget at valuable resources and need to be balanced. 

For the end-user the responsibility is transparency and safety. If they provide me information, I must not use it in a way that might possibly harm them, and that the agent's behavior is predictable and understandable, even if AI is a black box entity. In the future there might be movement towards more transparency and interpretability with AI learning models in order to help promote ethics and safety.
