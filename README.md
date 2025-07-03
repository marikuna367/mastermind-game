How the Code Works
Code Generation
The program randomly selects 4 colors (with possible repeats) from a list of valid colors (R, G, B, Y, W, O).
User Input
The player is prompted to guess the code by entering 4 color letters separated by spaces. The input is validated to ensure it's the right length and contains only valid colors.
Checking the Guess
Each guess is compared to the secret code:
Correct Position: Right color in the right spot.
Incorrect Position: Right color in the wrong spot.
Feedback Loop
After each guess, the program gives feedback on how many colors are correct and in the correct/incorrect position. The player has 10 tries to guess the code.
Win/Lose Condition
If the player guesses all 4 colors in the correct positions, they win.
If all 10 tries are used without cracking the code, the correct answer is revealed.
