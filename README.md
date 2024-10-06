Assignment 3: Hangman Game
Introduction
The Hangman game is a word puzzle game where one player thinks of a word, and the
other player tries to guess it one letter at a time. The game continues until the guesser
either guesses the word correctly or makes too many incorrect guesses.
Game Rules
In this assignment, you will implement a text-based version of the Hangman game with
the following rules:
• The player chooses the words’ length (typically 6 and above).
• The computer selects a random word from a predefined list of words (a list of all En-
glish words is available at this link: https://github.com/dwyl/english-words/
blob/master/words.txt
• The player’s goal is to guess the word letter by letter.
• The player has a limited number of incorrect guesses (e.g., 6 incorrect guesses).
• After each incorrect guess, a part of a hanging man is drawn.
• The player wins if they guess the word correctly before running out of guesses.
Otherwise, the computer wins.
Requirements
Create a Python program that:
• Sorts the words in the file by length and use a dictionary to store the sorted data.
1
• Selects a random word with a length that is specified by the player.
• Allows the player to guess one letter at a time.
• Tracks the incorrect guesses and displays the hangman parts accordingly.
• Ends the game when the player guesses the word correctly or runs out of guesses.
• Implements a scoring system (e.g., +10 points for each correct letter guess, -5 points
for each incorrect guess).
• Displays the player’s score at the end of the game.
• Offers the player the option to play again.
