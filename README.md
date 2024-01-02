# Hangman Game

Hi,This simple Hangman game is implemented in Python and split into three files.

# Files

1. **main.py**: Contains the main code for the Hangman game. It imports necessary modules, defines the game logic, and starts the game.
   
2. **hangman_words.py**: Contains a list of words that can be used as potential words for the Hangman game. The game randomly selects a word from this list.

3. **hangman_art.py**: Contains ASCII art for the Hangman game's logo and a list of ASCII art for the different stages of the hangman. The ASCII art is displayed as the player makes incorrect guesses.


#Game Rules:
You have 6 lives to guess the hidden word.
The game will display the current state of the word, with underscores representing unknown letters.
Guess a letter by entering it and pressing Enter.
If the letter is correct, it will be revealed in the word.
If the letter is incorrect, you will lose a life, and the hangman will progress through different stages.
The game continues until you either guess the entire word or run out of lives.

#Winning and Losing:
If you successfully guess the entire word before running out of lives, you win the game.
If you run out of lives, the game ends, and you lose.
