# Dice Roller Game

A simple interactive Python game that lets you roll a dice in the terminal. Each round, you get to roll the dice three times, and you can keep playing as many rounds as you like!

## Features

- Simulates rolling a standard 6-sided dice.
- Each round gives you 3 rolls.
- Tracks the total number of rolls you've made.
- Simple, text-based interface.
- Option to continue playing or quit after each round.

## Getting Started

### Prerequisites

- Make sure Python 3.x is installed before proceeding.

### How to Run

1. **Download the Script**  
   Save the code to a file, for example: `dice_roller.py`

2. **Run the Script**  
   Open a terminal and run:
   ```bash
   python dice_roller.py
   ```

3. **Play the Game**  
   - Press Enter to roll the dice when prompted.
   - After 3 rolls, decide if you want to play another round by entering `y` or `n`.

## Example Output

```
🎲 Welcome to the Dice Roller Game!
Press Enter to roll the dice...
You rolled a 5 !

Press Enter to roll the dice...
You rolled a 2 !

Press Enter to roll the dice...
You rolled a 6 !

Do you want to roll again? (y/n): n
You rolled the dice 3 times. Thanks for playing! 🎉
```

## Customization

- You can change the number of rolls per round by modifying the `for i in range(3):` line in the `rolling` function.
- Feel free to add more features, such as rolling multiple dice or keeping track of the highest roll!

## License

This project is open source and free to use for educational or personal projects.

---

Enjoy rolling!
