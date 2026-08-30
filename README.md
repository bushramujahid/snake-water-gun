# Snake-Water-Gun Game

A simple Python command-line game implementing the classic Snake-Water-Gun game (similar to Rock-Paper-Scissors).

## Game Rules

The game follows these winning conditions:
- **Snake beats Water** (snake drinks water)
- **Water beats Gun** (water corrodes gun)
- **Gun beats Snake** (gun shoots snake)
- **Same choices = Draw**

## How to Play

1. Run the program:
   ```bash
   python main.py
   ```

2. The computer randomly selects Snake (s), Water (w), or Gun (g)

3. You are prompted to enter your choice:
   - `s` for Snake
   - `w` for Water
   - `g` for Gun

4. The game displays both choices and announces the result:
   - "You Win!" - You beat the computer
   - "You lose!" - Computer beat you
   - "It's a draw!" - Both chose the same

## Requirements

- Python 3.x
- No external libraries required

## File Structure

- `main.py` - Main game script

## Example Gameplay

```
Computer's turn: Snake(s), Water(w), Gun(g)
Your turn: Snake(s), Water(w), Gun(g): s

You win: s

Computer win: w
You lose!
```

## Author

Created as a mini project from "Code with Harry" Python course
