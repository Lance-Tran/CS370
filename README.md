# CS370
SNHU CS370 Submission

## Briefly explain the work that you did on this project: What code were you given? What code did you create yourself?
Code Given: I was provided with the TreasureMaze.py environment and the base ExperienceReplay.py class. This included the game logic for the grid (walls, treasure, and pits) and the memory buffer used to store the agent’s past experiences.
Code Created: I designed the Neural Network architecture (DQN) and the qtrain loop. This required implementing the Epsilon-Greedy logic to handle exploration and exploitation, the Bellman Equation to update Q-values, and the decay function to transition the agent from random movement to goal-oriented navigation. I also handled the integration between the environment's state and the model's predictions.

## Connect your learning from throughout this course to the larger field of computer science: What do computer scientists do and why does it matter? How do I approach a problem as a computer scientist?

Computer scientists are architects of efficiency. They don't just "write code"; they solve problems by translating abstract human needs into logical, repeatable processes.

Why it matters: In the larger field, this matters because it allows us to scale solutions. Whether it's a pirate finding treasure or a medical AI identifying a tumor, the underlying discipline of optimizing an algorithm (like the one I built) saves time, money, and human effort.


To approach a problem as a computer scientist is to embrace Decomposition and Abstraction.

Instead of looking at the "Treasure Hunt" as one big task, I broke it down into:

State Representation: How does the computer "see" the map?

Reward Function: How do we define success?

Iteration: How do we move from "Zero-Value Inertia" to an optimal path?

This methodical approach—breaking a massive obstacle into tiny, solvable logic gates—is the hallmark of the discipline.

## What are my ethical responsibilities to the end user and the organization?
To the Organization: I must ensure the code is efficient, maintainable, and cost-effective. As I discussed in my critique, balancing training time with "thoroughness" is a fiduciary duty to the organization paying for the compute power.

To the End User: My responsibility is Transparency and Safety. Since AI can be a "black box," I must ensure the agent’s behavior is predictable. For instance, in a real-world scenario, an agent that settles for a "suboptimal win" might be dangerous or wasteful. My responsibility is to design systems that are not only functional but also interpretable and fair.
