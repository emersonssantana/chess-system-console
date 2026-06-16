# Chess System Console ♟️

A complete, interactive, and turn-based Chess Match Engine built entirely in C# running directly in the command line interface (CLI). This project was developed to apply core and advanced concepts of Object-Oriented Programming (OOP) and systems architecture.

## 🚀 Key Features

* **Complete Chess Logic:** Full implementation of standard chess rules, including turn management, piece movement validation, and win/draw conditions like **Check** and **Checkmate**.
* **Special Moves:** Full support for advanced chess moves:
  * **Castling** (Roque pequeno e Roque grande)
  * **En Passant**
  * **Promotion** (Promoção de peão)
* **Custom Exception Handling:** Built-in validation system that catches illegal moves, out-of-bounds positioning, or target position errors without crashing the application.
* **Interactive Board Rendering:** A clean matrix-based visual display in the console that dynamically highlights the current board state and captures user inputs smoothly.

## 🛠️ Architecture & C# Concepts Applied

This system was designed with strict separation of concerns, dividing the application into logical layers:

* **Board Layer (`board`):** Manages the core matrix structures, positions, and basic piece containment rules.
* **Chess Layer (`chess`):** Implements specific chess rule overrides, game flow, and piece-specific behaviors.
* **Object-Oriented Programming (OOP):** Extensive use of:
  * **Encapsulation & Access Modifiers:** Securing the state of the board and match.
  * **Inheritance & Polymorphism:** A base `Piece` class with unique movement behaviors overridden by specific pieces (King, Rook, Pawn, etc.).
* **Matrix Manipulation:** Dynamic handling of 2D arrays to update the 8x8 board efficiently after every move.

## 🔧 How to Run

1. Clone this repository:
```bash
git clone [https://github.com/emersonssantana/chess-system-console.git]
