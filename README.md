# MCTS-Based Capture Agents for Pacman AI

This project implements a team of capture agents for the Pacman Capture the Flag challenge using Monte Carlo Tree Search (MCTS). The agents are divided into two roles:

- **OffensiveMCTSAgent:** Uses MCTS to plan aggressive moves when pursuing food and evading enemies.
- **DefensiveMCTSAgent:** Uses MCTS and patrol strategies to defend territory and intercept invaders.

## Features

- **MCTS Implementation:** Includes node expansion, simulation, evaluation, and backpropagation to guide decision-making.
- **Dual Role Agents:** Separate offensive and defensive strategies tailored to in-game situations.
- **Seamless Integration:** Designed to work within the UC Berkeley Pacman AI projects framework.

## Setup

1. **Clone the Repository:**

2. **Integration:**
- Place the source file (e.g., `GEAK (3).py`) in your Pacman project’s directory where team agents are defined.
- Ensure the project includes the original UC Berkeley files (e.g., `captureAgents.py`, `game.py`, etc.) to support integration.

3. **Usage:**
- The team is created using the `createTeam` function defined in the file.
- Run the Pacman Capture the Flag game and select this team configuration to see the agents in action.

## Attribution

This project is based on the UC Berkeley Pacman AI projects. Please retain the original licensing and attribution information as provided.

## License

[MIT License]
