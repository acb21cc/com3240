# Grid World Lava Environment Simulation

This project simulates reinforcement learning algorithms SARSA and Q-Learning to navigate a robot through a grid world called "Lava", where the robot encounters various obstacles and seeks artifacts with associated rewards.
## Contributors
- **Code Written by:**Chen Chen

## Environment Setup

The grid world is designed with different setups for each task:
- **Task 1**: Single artifact with deterministic rewards.
- **Task 2**: Dual artifacts with stochastic rewards.
- **Task 3**: Stochastic transitions and rewards.

## Getting Started

### Prerequisites

This project is implemented in Python and requires the following packages:
- NumPy
- Matplotlib

You can install these packages using pip:

\```bash
pip install numpy matplotlib
\```

### Files

- `Assignment_empty.ipynb`: The Jupyter Notebook containing the primary code for setting up environments, defining the SARSA and Q-Learning algorithms, and running simulations.
- `gridworld_env.py`: Contains definitions for the `GridWorld` class for different task environments.
- `utils.py`: Contains utility functions, including `paint_gridworld` to visualize the grid.

### Running the Simulation

1. Clone the repository or download the files to your local machine.
2. Open the `Assignment_empty.ipynb` file in Jupyter Notebook or JupyterLab.
3. Run the cells sequentially to simulate each task and visualize the results.

## Implementation Details

### SARSA Agent

Implements the SARSA learning algorithm, updating policies based on actions taken according to the current policy.

### Q-Learning Agent

Uses the Q-Learning method, learning the optimal policy through actions derived from a greedy policy, independent of the agent's current action.

### Visualization

Visualizations are generated in `Assignment_empty.ipynb`, including plots of learning curves that show cumulative rewards and steps per episode for each task.

## Results and Analysis

- Analyze how learning rate, discount factor, and exploration rate affect learning performance.
- Compare SARSA and Q-Learning regarding their adaptability and efficiency in learning.
- Discuss the impact of stochastic elements (transitions and rewards) on the learning behavior of agents.

## License

This project is open-sourced under the MIT License.

## Acknowledgments

- Appreciation to the creators and maintainers of the NumPy and Matplotlib libraries.
- Inspired by classical reinforcement learning challenges.