# Snake Game AI

This is a Java implementation of the classic Snake game, featuring an AI that learns to play the game through evolutionary algorithms.

## Features

- **Population-based Learning**: The AI learns to play the game through natural selection and genetic algorithms.
- **Adjustable Parameters**: Various parameters such as mutation rate, hidden layers, and FPS can be adjusted to optimize learning.
- **Graphical Interface**: The game provides a graphical interface to visualize the learning progress and the snake's decision-making process.

## Usage

To run the game, simply execute the main program. You can interact with the game using the following controls:

- Arrow keys: Control the snake's movement (if humanPlaying is set to true)
- Mouse click: Perform actions such as loading and saving the snake model, adjusting mutation rate, and displaying evolution graph.

## Configuration

- `SIZE`: Size of the game grid.
- `hidden_nodes`: Number of nodes in each hidden layer.
- `hidden_layers`: Number of hidden layers.
- `fps`: Frames per second (adjustable for performance).
- `mutationRate`: Rate of mutation for genetic algorithms.
- `humanPlaying`: Set to true to play the game manually, false to let the AI play.
- `replayBest`: Display only the best snake of each generation.
- `seeVision`: Enable to visualize the snake's vision.
- `modelLoaded`: Set to true if a pre-trained model is loaded.

## Files

- `Snake.java`: Contains the main game logic and AI implementation.
- `Population.java`: Manages the population of snakes and implements genetic algorithms.
- `EvolutionGraph.java`: Handles visualization of the evolution graph.
- `Button.java`: Provides functionality for buttons in the graphical interface.

## Requirements

- Java Development Kit (JDK)
- Processing library (for graphical interface)

## Credits

This project is inspired by various tutorials and examples on genetic algorithms and game development.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
