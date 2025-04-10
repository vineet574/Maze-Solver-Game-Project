# Maze-Solver-Game-Project

# Maze Solver Game

A simple console-based Maze Solver game implemented in Java. The project generates a random maze and uses an AI algorithm to find the shortest path from the start (`S`) to the endpoint (`E`). The game is both interactive and educational, showcasing problem-solving techniques like Breadth-First Search (BFS).

---

## Features

- **Random Maze Generation:** Dynamically creates a maze with open paths (`.`) and walls (`#`).
- **AI Solver:** The program uses the BFS algorithm to calculate the shortest path to the endpoint.
- **Interactive Gameplay (optional):** Allows future expansion for user interaction to solve the maze manually.

---

## How to Run the Project

1. **Clone or Download the Repository:**

git clone <repository-url>

Navigate to the project directory.

2. **Compile the Code:**
javac MazeSolver.java


3. **Run the Program:**
java MazeSolver


---

## Project Structure

- **Main Class:** `MazeSolver`  
The core of the project, containing:
- Maze generation logic.
- AI solver logic (BFS algorithm).
- Maze visualization.

---

## How It Works

1. The program initializes a random maze with specified dimensions (default: 10x10).
2. The maze is displayed in the console, with:
- `S` as the starting point.
- `E` as the endpoint.
- `.` representing open paths.
- `#` representing walls.
3. The BFS algorithm calculates the shortest path.
4. If a path is found, the program prints `Reached the endpoint!`. If no path exists, it displays `No path found!`.

---

## Future Enhancements

- Add difficulty levels with larger or more complex mazes.
- Allow users to input custom maze dimensions or configurations.
- Implement a visual representation of the shortest path in the console.
- Enable manual gameplay for user interaction.

---

## Technologies Used

- **Java**
- **Breadth-First Search Algorithm (BFS)**
