# Viking-Chess-Hnefatafi

## 📖 Overview

This project implements a chess-like game, focusing on core gameplay mechanics, graphical user interface (GUI), and game logic testing. The project is modular, designed for flexibility and extensibility, making it ideal for developing customized board games based on chess-like rules.

---

## 🛠️ Features

- **Core Gameplay Mechanics**: Handles player turns, move validation, and game progression.
- **Graphical User Interface (GUI)**: Provides an interactive interface for gameplay.
- **Game Logic**: Implements rules and logic for moves and player interactions.
- **Game Statistics**: Tracks and displays game stats such as moves and players’ performance.
- **Comprehensive Testing**: Includes unit tests for verifying game logic functionality.

---

## 📂 Project Structure

- **`Main.java`**: Entry point of the application.
- **`ConcretePiece.java`**: Defines the properties and behaviors of game pieces.
- **`King.java`**: Specialized logic for the "King" piece.
- **`GameLogic.java`**: Implements the core game rules and logic.
- **`GameLogicTest.java`**: Unit tests for validating game logic.
- **`GameStats.java`**: Tracks and manages game statistics.
- **`ConcretePlayer.java`**: Defines player behaviors and interactions.
- **`Move.java`**: Encapsulates logic for game moves.
- **`GUI_for_chess_like_games.java`**: Provides the graphical user interface for the game.
- **`Position.java`**: Represents positions on the game board.
- **`Player.java`**: Encapsulates player-specific logic and attributes.
- **`PlayableLogic.java`**: Interfaces for playable game logic.
- **`Piece.java`**: Abstract class defining common properties and methods for game pieces.
- **`Pawn.java`**: Implements logic specific to the "Pawn" piece.

## 🎮 Gameplay Instructions

1. Launch the application using the steps above.
2. Use the GUI to select and move pieces according to game rules.
3. View game stats and player performance updates in real-time.

---

## 🧪 Testing

This project includes unit tests to ensure robust game logic. Run the tests using JUnit or your IDE’s integrated test runner.

- **Test Coverage**: Validates move logic, piece interactions, and game state updates.

---

## 🌟 Features to Explore

- Custom piece definitions with `ConcretePiece.java`.
- Dynamic gameplay using `Move.java`.
- Interactive GUI with `GUI_for_chess_like_games.java`.

---

## 🚀 How to Run

1. **Prerequisites**:

   - Java Development Kit (JDK) 11 or higher.
   - A Java IDE or terminal with Java support.

2. **Compile the Project**:

   ```bash
   javac *.java
   ```

3. **Run the Application**:

   ```bash
   java Main
   ```

4. **Run Tests**: Use a testing framework like JUnit to execute `GameLogicTest.java`.

---
