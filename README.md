# Maze Generator and Solver

This project is a graphical maze generator and solver built using Python's Tkinter library. The maze can be generated with random walls, ensuring there's always a path from the start to the end. It uses depth-first search for both generation and solving the maze, but can be extended with other algorithms.

## Requirements

- Python 3.10 or higher
- Tkinter library

## Setup

Before diving into the project, make sure you have the following:

- A code editor (VS Code is recommended)
- A command line (Bash for Mac OS/Linux, WSL for Windows)

### Installing Tkinter

Make sure you have Tkinter installed. Run the following command to check if Tkinter is installed:

```bash
python -m tkinter
```

If you encounter issues, install the necessary dependencies:

- On Ubuntu:
  ```bash
  sudo apt-get install python3-tk
  ```
- On Mac OS:
  ```bash
  brew install python-tk
  ```

## Running the Project

To run the project execute the script with:

```bash
python main.py
```

![Maze Example](maze.gif)

## Future Ideas

- Implement other solving algorithms like breadth-first search or A\*
- Enhance the visuals with different colors and animations
- Add user interface elements to allow configuration changes
- Create larger and more complex mazes
- Convert the maze into a game where users can navigate through it
- Allow the user to race an algorithm
- Make it 3-dimensional
- Time the various algorithms and compare their performance

Feel free to contribute and make this project even more awesome!

## License

This project is licensed under the MIT License.
