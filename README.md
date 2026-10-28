
# Week 1: Architectural Planning for a Simulation Engine

## Project Overview
This project focuses on designing a basic simulation engine architecture using C++. The engine represents a virtual environment with entities that move and update over time.

## Objectives
- Plan a modular simulation engine.
- Understand object-oriented programming in C++.
- Organize entities and simulation updates.
- Explore design patterns and software architecture.

## Components
1. **Entity:** Stores entity ID, name, position, and velocity.
2. **EntityFactory:** Creates entities using the Factory Pattern.
3. **World:** Stores entities and updates their state.
4. **SimulationManager:** Controls the simulation workflow.
5. **Main Function:** Initializes and runs the simulation.

## Design Patterns
- **Factory Pattern:** Centralizes entity creation.
- **Modular Design:** Separates responsibilities into classes.
- **Object-Oriented Design:** Uses classes, encapsulation, and methods.

## Technologies Used
- C++
- Standard Template Library (STL)
- `vector`
- `memory`
- `string`
- `iostream`

## Project Structure
```text
Week1-Simulation-Engine/
├── main.cpp
└── README.md
```

## How to Run

1. Install a C++ compiler such as GCC.
2. Save the program as `main.cpp`.
3. Compile the program:

```bash
g++ -std=c++17 main.cpp -o simulation
```

4. Run on Linux or macOS:

```bash
./simulation
```

On Windows:

```bash
simulation.exe
```

## Expected Output
The program displays simulation steps and the updated positions of the Player and Enemy entities.

## Future Improvements
- Add input handling.
- Implement physics and collision detection.
- Add an observer/event system.
- Introduce a rendering interface.
- Write unit tests.

## Conclusion
This project demonstrates a basic C++ simulation engine structure and provides a foundation for further development.
