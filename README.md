# Blackjack Game

This repository contains a Python implementation of the classic Blackjack card game, allowing players to compete against a computer dealer.

## Features

- **Interactive Gameplay**: Engage in a turn-based game against the dealer, following standard Blackjack rules.
- **Card Dealing and Shuffling**: Simulates a real deck of cards with shuffling and dealing functionalities.
- **Hand Value Calculation**: Automatically calculates and displays the value of hands, accounting for Aces as 1 or 11.
- **Betting System**: Players can place bets and track their chip total throughout the game.

## Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/masood2004/Blackjack_Game.git
   ```

2. **Navigate to the project directory**:

   ```bash
   cd Blackjack_Game
   ```

3. **Ensure Python is installed**:

   This game requires Python 3.x. You can download it from the [official website](https://www.python.org/downloads/).

## Usage

Run the `main.py` file to start the game:

```bash
python main.py
```

## How to Play

1. **Starting the Game**: Upon running the game, you'll be prompted to place a bet.
2. **Dealing Cards**: Both you and the dealer receive two cards; one of the dealer's cards remains hidden.
3. **Player's Turn**:
   - Choose to 'Hit' to receive another card or 'Stand' to end your turn.
   - Aim to get as close to 21 as possible without exceeding it.
4. **Dealer's Turn**: The dealer reveals the hidden card and must hit until reaching at least 17.
5. **Determining the Outcome**:
   - If your hand exceeds 21, you bust and lose your bet.
   - If the dealer busts, you win and receive double your bet.
   - If neither busts, the hand closest to 21 wins.
6. **Playing Again**: After each round, you can choose to play another hand or exit the game.

## License

This project is licensed under the MIT License. See the [LICENSE](https://github.com/masood2004/Blackjack_Game/blob/master/LICENSE) file for details.

## Acknowledgments

This project serves as a practice exercise for learning Python and implementing game logic, inspired by the classic Blackjack card game.

Enjoy the game and test your luck against the dealer! 
