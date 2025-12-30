# C++: Conway's Game of Life
**University Year 1 | Game Programming Fundamentals**

A technical implementation of Conway’s Game of Life, focusing on cellular automata logic, 2D array manipulation, and real-time state simulation using the SFML library.

> **[🔗 View the full technical breakdown on my Portfolio](https://sites.google.com/view/myles-coleman/projects/game-software-engineering)**

## 🕹️ Project Overview
This project explores the principles of simulation engineering through Conway's Game of Life. Built upon the foundations of a custom grid-based framework, it features a complete simulation engine that validates neighbour counts and applies survival/reproduction rules across a dynamic coordinate system.

## 🛠️ Key Technical Features

### Simulation & Algorithmic Logic
* **Cellular Automata Implementation:** Engineered a rule-based engine to handle the four core states of Conway's simulation: underpopulation, survival, overpopulation, and reproduction.
* **Neighbour Counting Algorithm:** Developed a robust neighbour detection system that iterates through adjacent grid coordinates to calculate live-cell proximity for every cell in the 20x20 grid.
* **Generation Buffer Management:** Implemented a dual-buffer system using a `nextMap` array to calculate state changes independently of the current display, ensuring that the entire generation updates simultaneously.

### Engineering Foundation
* **Architectural Evolution:** Developed as a technical evolution of my [C++ Grid-Based Maze System](https://github.com/MylesColeman/CPP-Grid-Maze-System), demonstrating effective code reuse and the modularity of the SFML-based framework.
* **Grid-Based Data Structures:** Managed the simulation world via 2D `char` arrays, allowing for efficient coordinate-to-cell mapping and real-time rendering.
* **State Persistence:** Utilises File I/O foundations to load initial "seed" world states from plain-text files, allowing for custom simulation starts.

## 💻 Technical Specs
* **Language:** C++
* **Library:** SFML (Simple and Fast Multimedia Library)
* **Compiler:** Visual Studio
* **Logic:** Cellular Automata (Conway's Rules)
