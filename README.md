# Snake Game Template

Welcome to the Snake Game template! This classic game is implemented in Python 3.10 using the Pygame framework and the Entity-Component-System (ECS) design pattern. As a student, you're encouraged to fork this repository and use GitHub Codespaces for a seamless coding experience.

## Directory Structure

Snake_Game
│
├── LICENSE # The license file for this project.
├── README.md # This documentation file.
├── main.py # The main script to run the game.
├── src # Source code directory.
│ ├── components # Components used in the ECS design pattern.
│ │ ├── position.py # Defines the position component.
│ │ ├── renderable.py # Defines the renderable component.
│ │ └── velocity.py # Defines the velocity component.
│ ├── entities # Game entities like the snake and food.
│ │ ├── food.py # Defines the food entity.
│ │ └── snake.py # Defines the snake entity.
│ └── systems # Systems that handle game logic.
│ ├── collision.py # Handles collision logic.
│ ├── movement.py # Handles movement logic.
│ └── render.py # Handles rendering logic.
└── tests # Tests for the source code.
├── components # Tests for components.
│ ├── test_position.py # Tests for the position component.
│ ├── test_renderable.py # Tests for the renderable component.
│ └── test_velocity.py # Tests for the velocity component.
├── entities # Tests for entities.
│ ├── test_food.py # Tests for the food entity.
│ └── test_snake.py # Tests for the snake entity.
└── systems # Tests for systems.
├── test_collision.py # Tests for the collision system.
├── test_movement.py # Tests for the movement system.
└── test_render.py # Tests for the rendering system.

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
