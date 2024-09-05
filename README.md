# Hangman Game

Welcome to the **Hangman Game**, a classic word-guessing game implemented in Python. This project is a simple yet fun console-based application where players try to guess a secret word, one letter at a time, with a limited number of wrong guesses allowed.

<img src="https://github.com/user-attachments/assets/d3fbd2aa-9fd9-4c93-9f2c-5861eef75abc" alt="Slot Machine Picture" width="400"/>

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Usage](#usage)
- [Gameplay](#gameplay)

## Overview

Hangman is a word-guessing game where players attempt to guess the letters in a hidden word. For each incorrect guess, a part of the hangman is drawn. The game ends when the player either guesses the word correctly or the hangman drawing is complete.

## Features

- Randomly selects a word from a predefined list.
- Provides feedback on incorrect guesses by progressively drawing the hangman.
- Allows players to input guesses and checks for validity (single letter, alphabetical).
- Displays the current state of the guessed word with underscores for unguessed letters.
- Ends the game when the player either correctly guesses the word or reaches the maximum number of wrong guesses.

## Usage
- The game will start automatically and select a random word from the wordlist.py file.
- Players will be prompted to enter a guess (single letter).
- The game will display the hangman progress and the current state of the guessed word.
- Keep guessing until you either complete the word or the hangman drawing is fully complete.
  
## Gameplay
- At the start, the game randomly selects a word from a list.
- You have a limited number of wrong guesses (6 chances) before the game ends.
- Each correct guess reveals the position of the letter in the word.
- Each incorrect guess adds a part to the hangman drawing.
- Win by guessing all letters in the word before the hangman is fully drawn.
