# Tic-Tac-Toe (C++)

A simple **console-based Tic-Tac-Toe** game written in **C++**.

## Features

- 2-player gameplay (Player 1 vs Player 2)
- Player 1 can choose their marker (**X** or **O**)
- Input validation:
  - only allows positions **1–9**
  - prevents overwriting an already-taken position
- Automatically detects:
  - win (rows / columns / diagonals)
  - tie (when the board is full)

## Files

- `tic.cpp` — main C++ source code
- `tic.exe` / `a.exe` — compiled Windows executables (optional to keep in the repo)

## How to Compile and Run

### Using g++ (Linux / macOS / MinGW on Windows)

```bash
g++ tic.cpp -o tic-tac-toe
./tic-tac-toe
```

### Using MSVC (Windows / Visual Studio Developer Command Prompt)

```bat
cl tic.cpp
./tic.exe
```

## How to Play

1. Run the program.
2. **Player 1** chooses a marker: `X` or `O`.
3. Players take turns selecting a position from **1 to 9**:

```
 1 | 2 | 3
---|---|---
 4 | 5 | 6
---|---|---
 7 | 8 | 9
```

4. The game announces the winner or a tie.

## Notes

- The board is displayed after every move.
- If Player 1 enters an invalid marker, the game defaults to **X**.

## License

No license specified yet. If you want, add a `LICENSE` file (for example: MIT).