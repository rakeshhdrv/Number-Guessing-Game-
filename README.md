# 🎯 Number Guessing Game

A simple and interactive number guessing game built with Python. Test your luck and see how many attempts it takes to guess the randomly generated number!

## 🎮 How to Play

1. **Set the Range**: Enter a positive number to set the upper limit of the guessing range
2. **Start Guessing**: The game will generate a random number between 1 and your chosen limit
3. **Get Hints**: After each guess, you'll receive feedback:
   - "Your guess is too high" - if your guess is above the target
   - "Your guess is too low" - if your guess is below the target
   - "Matched" - when you find the correct number!
4. **Track Your Score**: The game counts your attempts and displays the final count

## 🚀 Getting Started

### Prerequisites
- Python 3.x installed on your system

### Installation & Running
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/number-guessing-game.git
   ```

2. Navigate to the project directory:
   ```bash
   cd number-guessing-game
   ```

3. Run the game:
   ```bash
   python guessing_game.py
   ```

## 📝 Example Gameplay

```
Type the number? 50
Guess the number? 25
Your guess is too high
Guess the number? 12
Your guess is too low
Guess the number? 18
Matched
Your answer got matched in 3 guesses : )
```

## ✨ Features

- **Input Validation**: Ensures only valid positive numbers are accepted
- **Error Handling**: Graceful handling of invalid inputs during gameplay
- **User-Friendly**: Clear prompts and helpful feedback messages
- **Score Tracking**: Counts and displays the number of attempts taken

## 🛠️ Technical Details

- **Language**: Python
- **Libraries Used**: `random` (built-in)
- **Input Method**: Command-line interface
- **Error Handling**: Validates numeric inputs and range constraints

## 🎯 Game Logic

The game uses Python's `random.randint()` function to generate a number within the specified range. It implements a simple binary search-like feedback system to guide players toward the correct answer.

## 🤝 Contributing

Feel free to fork this repository and submit pull requests for any improvements:
- Enhanced UI/UX
- Difficulty levels
- High score tracking
- GUI implementation

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🎉 Acknowledgments

- Built as a learning project to practice Python fundamentals
- Great for beginners learning loops, conditionals, and user input handling

---

**Enjoy the game and happy guessing! 🎲**
