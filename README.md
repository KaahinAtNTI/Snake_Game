# Snake Game

A classic Snake game implemented in Python using the Pygame framework and the Entity-Component-System (ECS) design pattern.

## Getting Started

### Prerequisites

- Python 3.x
- Pygame

You can install Pygame using pip:

```
pip install pygame
```

### Running the Game

1. Clone the repository:

```
git clone <repository-url>
```

2. Navigate to the game directory:

```
cd snake_game
```

3. Run the `main.py` script to start the game:

```
python main.py
```

## Folder Structure

- `src/`: Contains the source code for the game.
  - `entities/`: Contains entity definitions like Snake and Food.
  - `components/`: Contains component definitions like Position, Velocity, and Renderable.
  - `systems/`: Contains system logic like Movement, Rendering, and Collision handling.
- `tests/`: Contains unit tests for the game components and logic.

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.