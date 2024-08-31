# 👑 N-Queen Visualizer 👑

The N-Queen Visualizer is an interactive web application designed to visualize the N-Queen problem's solutions using JavaScript, HTML, and CSS. This project allows users to select a board size and visually observe how the N-Queen solution is computed step-by-step.

Live Demo: [N-Queen Visualizer](https://amit-10101.github.io/N-Queen-Visualizer/)

## Features

-   **Dynamic Board Size**: Users can select the size of the chessboard (from 4x4 to 20x20) to visualize the N-Queen problem.
-   **Step-by-Step Visualization**: The application visually demonstrates each step in solving the N-Queen problem, including backtracking.
-   **Interactive UI**: Simple and interactive user interface for better user experience.

## Installation

To set up the N-Queen Visualizer locally, follow these steps:

1. Clone the repository:

    ```bash
    git clone https://github.com/Amit-10101/N-Queen-Visualizer.git
    ```

2. Navigate to the project directory:

    ```bash
    cd N-Queen-Visualizer
    ```

3. Open the `index.html` file in your browser to see the application in action.

## Usage

To use the visualizer:

1. Open the index-html file in a web browser.
2. Use the input field to select the desired board size (between 4 and 20).
3. Click the "Visualize" button to start the visualization.

## How It Works

The application uses a backtracking algorithm to solve the N-Queen problem. The key functions include:

-   `visualizeNQueen()`: Initializes the board and starts the solving process.

-   `solveNQ()`: Main function that attempts to place queens on the board using `solveNQUtil()`.

-   `solveNQUtil()`: Recursive utility function to place queens correctly on the board.

-   `isSafe()`: Checks if a queen can be placed on the board without conflicts.

-   `sleep()`: Utility function to delay actions for better visualization.

## Contributing

Contributions to the N-Queen Visualizer are welcome! If you have suggestions for
improvements or bug fixes, please open an issue or submit a pull request.
