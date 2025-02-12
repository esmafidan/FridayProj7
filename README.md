# FridayProj7
Welcome to the Python Projects collection! This repository includes various interactive Python programs to practice foundational programming skills, including classes, functions, loops, conditionals, and user input handling. Each project is designed to improve understanding of specific concepts and provide hands-on experience with Python's functionality.

## Table of Contents:

Project 1: Mad Lib Game
Project 2: Lottery Number Generator
Project 3: Number Guessing Game
Project 4: Trivia Study Program
Project 5: Text Color Changer
Project 6: Bank Account Management System

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


### Project 4: Trivia Study Program
Overview:
This project is an interactive trivia quiz that displays a series of questions, accepts answers from the user, and provides feedback on correctness. A dictionary is used to store questions and answers.

Expectations:

Use a dictionary to store questions as keys and answers as values.
Use a for loop to go through each question, prompting the user for their answer.
Provide feedback on whether each answer is correct, building knowledge of dictionary and looping structures.

Notes:
Define a dictionary with trivia questions as keys and their correct answers as values
Display a greeting message
Loop through each question and answer in the dictionary
Display the question to the user
Prompt the user to input their answer
Check if the user's answer matches the correct answer (case-insensitive)
Display a farewell message after all questions are answered


### Project 5: Text Color Changer
Overview:
This project allows the user to display text in different colors by calling specific functions that format the text with ANSI color codes. It’s a fun way to learn about functions, parameters, and return values.

Expectations:

Define five functions, each applying a different color format to the text.
Prompt the user to choose a color and display their input text in that color.
Reinforce skills with functions, parameters, and return values, as well as working with color formatting in the console.

Notes:
Define functions to format text in different colors
ANSI code for red text
ANSI code for blue text
ANSI code for green text
ANSI code for yellow text
ANSI code for purple text 
Main Program Logic
Prompt the user to choose a color and input a string of text
Display the user's text in the chosen color

### Project 6: Bank Account Management System
Overview:
This project simulates a simple bank account system. The program allows users to deposit, withdraw, and check their balance after entering their account number. It uses a BankAccount class to define attributes and methods related to account management.

Expectations:

Create a BankAccount class with methods for depositing, withdrawing, and checking the balance.
Use an indefinite loop to allow the user to continue performing actions on their account.
Provide practice with object-oriented programming concepts, including classes, attributes, methods, and loops.

Notes:
Define the BankAccount class
Initialize the account with an account number and a starting balance
Add the deposit amount to the balance
Subtract the withdrawal amount from the balance if funds are sufficient
Return the current balance
Create an instance of BankAccount
Start an indefinite loop for user interactions
Exit condition for the loop
Check if the account number matches the user's account
Prompt for deposit amount and call the deposit method
Prompt for withdrawal amount and call the withdraw method
Call the check_balance method to display the current balance