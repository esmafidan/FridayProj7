# FridayProj7
Welcome to the Python Projects collection! This repository includes various interactive Python programs to practice foundational programming skills, including classes, functions, loops, conditionals, and user input handling. Each project is designed to improve understanding of specific concepts and provide hands-on experience with Python's functionality.

## Table of Contents:

Project 1: Mad Lib Game
Project 2: Lottery Number Generator
Project 3: Number Guessing Game


## Project Details:

### Project 1: Mad Lib Game
Overview:
This project is a simple word game that allows users to create a fun story by filling in blanks with their own words, such as nouns, adjectives, and body parts. It demonstrates the basics of user input and string formatting.

Expectations:

Collect user input for specified types of words (e.g., nouns, adjectives).
Display a story template filled in with the user’s responses.
Reinforce skills in user interaction and basic string manipulation.

Notes:
Prompt the player for input
Combine the player's inputs into the story template
Print the completed story

### Project 2: Lottery Number Generator
Overview:
This project generates random numbers for a PowerBall ticket, allowing users to pick five numbers between 1 and 69, plus one number between 1 and 26. It uses the random module to simulate the lottery drawing.

Expectations:

Generate and display six random numbers (five white balls and one red ball).
Separate the last number from the others for clarity.
Practice using Python’s random module and basic print formatting.

Notes:
Import the random module to use the randint function for generating random numbers
Display a greeting message to the user
Generate five random numbers between 1 and 69 for the white balls
Generate a random number between 1 and 26 for the red PowerBall
Format the output with spaces between the numbers
First five numbers have one space between them, followed by three spaces before the PowerBall number
Display a farewell message to the user

### Project 3: Number Guessing Game
Overview:
A guessing game where the computer selects a random number between 1 and 10, and the user tries to guess the correct number. The game loops until the correct answer is guessed or the user chooses to quit.

Expectations:

Continuously prompt the user for guesses.
Use an if statement to check if the guess is correct, and a while loop to keep the game running until the user is successful.
Build comfort with looping structures, conditionals, and random number generation.

Notes:
Import the random module to generate a random number for the secret number
Display a greeting message and ask the user if they want to play
Check if the user wants to play the game
Generate a random number between 1 and 10
Initialize the guess variable
Start a loop that continues until the user guesses correctly
Ask the user for their guess and convert it to an integer
Check if the guess is correct
Prompt to try again if the guess is incorrect
Farewell message after the correct guess
If the user says no, print a message and end the program
