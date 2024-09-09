# Blackjack Game

Welcome to my version of the Blackjack game, a simple implementation of the classic card game in Python! This project allows the user to play a game of Blackjack against the computer.

[By my version I mean that this implementation does not account for the fact that when one card is drawn from the deck the probability of it appearing again in a hand is less likely or none.]
## Features

- **Card Dealing**: Draw random cards from a deck with values ranging from 2 to 11.
- **Score Calculation**: Automatically calculate scores based on the cards in hand and handle Blackjack and bust conditions.
- **Game Flow**: Play through a standard game of Blackjack, where you can choose to draw more cards or pass. The computer also draws cards until it reaches a certain score.
- **Game Outcome**: The game will determine and display the winner based on the final scores.

## How to Play

1. Run the `main.py` script.
2. When prompted, type `'y'` to start a new game or `'n'` to exit.
3. During the game, you can choose to draw another card or pass by typing `'y'` or `'n'`, respectively.
4. The game will automatically end once a win, loss, or draw condition is met.

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/amrita060404/Blackjack.git
   ```
2. Navigate into the project directory:
   ```bash
   cd Blackjack
   ```
3. Ensure you have Python 3.x installed. You can download it from [python.org](https://www.python.org/).

## Running the Game

To start the game, run:
```bash
python main.py
```

## Files

- `main.py`: Contains the main game logic and user interface.
- `art.py`: Contains ASCII art for the game logo.

## Contributions

Feel free to contribute to the project by opening issues or submitting pull requests. Any improvements or features you would like to see are welcome!
