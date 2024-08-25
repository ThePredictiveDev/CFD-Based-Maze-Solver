# Maze Solver Using Fluid Dynamics

This project is a Python-based maze solver that uses computational fluid dynamics to find and visualize the solution path through a maze.

## How It Works

1. **Preprocessing**: The maze image is converted into a binary matrix, where walls are represented by `0` and paths by `1`.
2. **Entry and Exit Detection**: The program dynamically detects the entry and exit points on the borders of the maze.
3. **Fluid Dynamics Simulation**: The fluid is simulated to flow through the maze, finding a path from the entry to the exit.
4. **Visualization**: The solution path is visualized using Matplotlib, with the fluid flow shown in shades of blue and the final path highlighted in blue.

## Requirements

- Python 3.x
- OpenCV (`cv2`)
- Matplotlib
- NumPy
- SciPy

You can install the required packages using `pip`:

```bash
pip install opencv-python-headless matplotlib numpy scipy
```

## Example

To use the maze solver, update the image path and run the script:

```python
solve_maze_with_fluid_dynamics(r'C:\path_to_your_maze_image\maze_image.jpeg')
```

## License
This project is licensed under the MIT License. 

