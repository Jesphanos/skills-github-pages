
"Try-It-Yourself-Exercises"
---
### 2025-02-28
---

Python Exercise Solutions
Introduction
Welcome to my Python exercise blog! Here, I'll be sharing my solutions to various Python exercises and projects. This blog is intended for beginners and intermediate learners who want to improve their Python skills.

Exercise Solutions
Exercise 1: Guessing Game
Problem Statement: Create a program that asks the user to guess a random number between 1 and 100.

Solution:

import random

def guessing_game():
    number_to_guess = random.randint(1, 100)
    guess = None
    while guess != number_to_guess:
        guess = int(input("Guess a number between 1 and 100: "))
        if guess < number_to_guess:
            print("Too low!")
        elif guess > number_to_guess:
            print("Too high!")
    print("Congratulations! You guessed the number.")

guessing_game()

Exercise 2: Rock, Paper, Scissors
Problem Statement: Create a program that allows two players to play Rock, Paper, Scissors.

Solution:

import random

def rock_paper_scissors():
    choices = ["rock", "paper", "scissors"]
    player1 = input("Player 1, enter your choice: ").lower()
    player2 = random.choice(choices)
    print(f"Player 2 chose: {player2}")
    if player1 == player2:
        print("It's a tie!")
    elif (player1 == "rock" and player2 == "scissors") or \
         (player1 == "scissors" and player2 == "paper") or \
         (player1 == "paper" and player2 == "rock"):
        print("Player 1 wins!")
    else:
        print("Player 2 wins!")

rock_paper_scissors()

Conclusion
I hope you found these solutions helpful! Remember to practice regularly and try to solve exercises on your own before looking at the solutions.

What's Next?
Stay tuned for more Python exercise solutions and projects! If you have any specific requests or questions, feel free to leave a comment below.

This is just a rough draft, and you can edit it later to fit your style and tone. Remember to:

- Format your code using Markdown syntax
- Provide clear explanations and comments for your code
- Encourage discussion and feedback in the comments
- Review and edit your post for clarity and accuracy before publishing
