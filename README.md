# Block Puzzle Solver

## Overview
This project is a solver for block puzzles, aiming to provide an efficient solution to rearranging blocks in a grid to achieve a desired configuration.

## Features
- **Automated Solutions:** Capable of finding solutions to various block puzzle configurations.
- **User-Friendly Interface:** Easy to navigate and use for both beginners and advanced users.
- **Custom Configuration:** Allows users to input their own block arrangements.

## Installation Instructions
1. **Clone the Repository:** 
   ```bash
   git clone https://github.com/Vietbaton/block-puzzle-solver.git
   cd block-puzzle-solver
   ```
2. **Install Dependencies:** 
   Ensure you have Python installed, then run:
   ```bash
   pip install -r requirements.txt
   ```
3. **Run the Application:** 
   ```bash
   python main.py
   ```

## How It Works
The program uses algorithms to analyze the grid configuration and apply suitable strategies to relocate blocks. It evaluates possible moves and aims to reach the target configuration in the least number of moves.

## Permissions Required
- **Read & Write Access:** To save puzzle configurations and solutions.
- **Execute:** Must be able to run Python scripts.

## Project Structure
```
block-puzzle-solver/
│
├── main.py          # Main application script
├── solver.py        # Contains the solving algorithms
├── README.md        # Project documentation
└── requirements.txt # List of dependencies
```

## Future Improvements
- **User Account System:** Implement user authentication for personalized experiences.
- **Enhanced Algorithms:** Research and apply more efficient solving algorithms.
- **Mobile Compatibility:** Adapt the interface for mobile devices for wider accessibility.