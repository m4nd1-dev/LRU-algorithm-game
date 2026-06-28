# LRU Algorithm Game

An interactive educational game built with Python and Tkinter to help users learn how the Least Recently Used (LRU) page replacement algorithm works.

The game presents a reference string and asks the player to fill in the frame contents step by step, then checks the answers and explains the LRU decisions.

## Features

- Interactive puzzle-style gameplay for learning LRU
- Randomly generated or user-entered reference strings
- Visual grid for frame contents across each step
- Automatic feedback on correct and incorrect entries
- Explanations of LRU replacement decisions
- Dark-themed GUI using ttkbootstrap

## How It Works

The program simulates the LRU page replacement algorithm and asks the player to predict which pages appear in each frame at each step.

You can:
- Start a new game
- Enter your own reference string
- Fill the grid with page numbers
- Use blank, `-`, or `_` for empty cells
- Check your answers and review the explanation panel

## Requirements

- Python 3.8+
- ttkbootstrap

Install the dependency with:

```bash
pip install ttkbootstrap
```

## Run the Game

From the project folder, run:

```bash
python "LRU Algorithm game code.py"
```

## Project Structure

- `LRU Algorithm game code.py` - Main game application
- `LRU Algorithm game.spec` - PyInstaller specification file
- `build/` - Build output files
- `dist/` - Distribution output folder

## Example

A sample reference string might look like this:

```text
1 2 3 1 4 2 5 1 2 3
```

The game uses this sequence to simulate the LRU behavior and lets you test your understanding.

## License

This project is open-source and available for educational and personal use.

## Contribution

Feel free to fork this project, improve it, and submit pull requests.
