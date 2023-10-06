# Snake Game Template

Welcome to the Snake Game template! This classic game is implemented in Python 3.10 using the Pygame framework and the Entity-Component-System (ECS) design pattern. As a student, you're encouraged to fork this repository and use GitHub Codespaces for a seamless coding experience.

## Project Structure Overview

- **LICENSE**: This file contains the licensing information for the Snake Game template, specifying the terms under which the code can be used, modified, and distributed.

- **README.md**: This is the primary documentation file for the Snake Game template, providing comprehensive instructions, information, and guidance on how to use, understand, and contribute to the project.

- **main.py**: This Python script serves as the entry point for running the Snake Game, containing the game's core logic and gameplay mechanics.

- **src/**: The source code directory containing the core implementation of the Snake Game, organized into subdirectories to manage various game components.

- **src/components/**: This subdirectory houses the components required for implementing the Entity-Component-System (ECS) design pattern, including position, renderable, and velocity components, which define the attributes and behaviors of game entities.

- **src/entities/**: Within this subdirectory, you'll find the definitions for game entities vital to the Snake Game, such as food and snake entities, which play crucial roles in the game's mechanics.

- **src/systems/**: This subdirectory contains the systems responsible for managing different aspects of game logic, including collision detection, movement mechanics, and rendering functions.

- **tests/**: This directory contains test files for validating the Snake Game's functionality using `pytest`.

- **tests/components/**: Subdirectory specifically dedicated to test files for game components, such as position, renderable, and velocity components.

- **tests/entities/**: This subdirectory houses test files related to game entities, encompassing tests for food and snake entities.

- **tests/systems/**: Within this subdirectory, you'll find test files that focus on game systems, which handle various game logic functionalities, including collision handling, movement mechanics, and rendering processes.

## Project Structure Diagram

![Snake Game Directory Structure](https://showme.redstarplugin.com/d/d:Q7qqVE9i)

## Getting Started with GitHub Codespaces

GitHub Codespaces provides a complete, configurable dev environment on top of a powerful VM. This means you can code, build, test, debug, and deploy without needing to set up a local environment.

### How to Fork and Use Codespaces:

1. **Fork the Repository:** At the top right of this repository, click the "Fork" button. This creates a copy of the repository in your own GitHub account.
2. **Access Your Fork:** Navigate to your own GitHub account and find the forked repository.
3. **Open in Codespaces:** Click the "Code" button and then select "Open with Codespaces". This will create a new Codespace using your forked repository.
4. **Start Coding:** Once the Codespace environment is ready, you can start coding and making changes.

🚨 **Important:** Always work within your forked repository, especially when using Codespaces. Avoid running the main repository on your local computer. Embrace this new way of coding with Codespaces for a streamlined experience.

## Installed Environment

In this Codespace, the following are pre-installed for your convenience:

- **Python:** Version 3.10
- **Pygame:** The popular game development library for Python.

## Running the Game

Once you're in your Codespace:

1. Navigate to the game directory:

2. Run the `main.py` script to start the game:

## Contributing

While this is a template, contributions to improve the base game are always welcome. For major changes, please open an issue first to discuss what you would like to change.

## License

This project is licensed under the MIT License.
