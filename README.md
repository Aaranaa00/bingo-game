# 🎱 Bingo Game

A console-based Bingo game where the player competes to complete their bingo card before running out of numbers. The game follows traditional Bingo rules, generating a random card and drawing numbers until a winner is determined.

## ✨ Features

- **Randomized bingo card generation** with a 3x5 grid.
- **Automated number drawing** from a pool of 90 numbers.
- **Automatic marking** of drawn numbers on the card.
- **Line detection announcement** when a row is completed.
- **Win condition** when all numbers on the card are marked.

## 🔍 How to Play

1. A 3x5 bingo card is generated with random numbers.
2. The game draws numbers one by one from a set of 90.
3. If a drawn number appears on the card, it is marked.
4. The game announces when a row is fully marked.
5. The player wins when all numbers are marked.

## 🛠 Data Structures Used

- **Lists (`list`)**:  
  - Used for storing the pool of numbers (1-90).  
  - Used to represent the bingo card as a list of lists (3x5 matrix).  
  - Used to store the numbers already drawn.  
- **Strings (`str`)**:  
  - Used to represent marked numbers (🔴) when a number is found on the card.  
- **Booleans (`bool`)**:  
  - Used for checking if a row (line) or full card (bingo) is completed.  

## 🚀 Future Improvements

- **Graphical interface** for better user experience.
- **Customizable game modes** (e.g., different card sizes).
- **Multiplayer support** for competitive play.

---

👾 Made with Python
