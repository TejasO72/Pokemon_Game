# 🎮 Java Pokémon Game

A console-based Pokémon game implemented in Java, showcasing Object-Oriented Programming principles.

## 🌟 Features

- Turn-based battle system
- Catch wild Pokémon
- Team management
- Inventory system with healing items
- Experience and leveling system

## 🏗️ Architecture

This project demonstrates key OOP concepts:

### 📦 Classes and Objects

- `Pokemon`: Represents individual Pokémon with attributes and behaviors
- `Move`: Encapsulates Pokémon attacks
- `Trainer`: Manages the player's team and inventory
- `Item`: Represents usable items like potions

### 🧬 Inheritance

While not explicitly shown, the structure allows for easy implementation of subclasses (e.g., different types of items or Pokémon)

### 🔒 Encapsulation

- Private attributes with public getters/setters
- Methods that operate on object's internal state

### 📊 Polymorphism

- Different Pokémon can use the same moves with varying effects
- Items can have different effects when used

## 🖥️ Main Game Loop

The `Main` class orchestrates the game flow:

1. Player creation and starter Pokémon selection
2. Main menu with options:
   - Battle wild Pokémon
   - View team
   - Use items
   - Quit game

## 🎭 Key OOP Principles Demonstrated

- **Abstraction**: Complex battle mechanics simplified into method calls
- **Encapsulation**: Internal state of objects protected, accessed via methods
- **Modularity**: Each class has a specific role, promoting code organization
- **Code Reuse**: Methods like `calculateDamage` used across different contexts


## 🛠️ How to Run

1. Compile all Java files using an IDE
2. Run the `Main` class
3. Follow on-screen prompts to play the game

Enjoy your Pokémon adventure in Java! 🌈✨
