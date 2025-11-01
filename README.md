
This set of code below is for a game that creates fun by guessing a number between 1 and 10
The code prompts the user to put a number and guides them to make the correct guess



Pseudocode

Start
 Put a random number between 1 and 10 → save it as `number_in_mind`
 Display: “I’m thinking of a number between 1 and 10.”
 Repeat the following steps until the user guesses correctly:
   - Ask the user to *enter a guess* and save it as `guess`
   - If`guess` < `number_in_mind`  
     → Display: “Too low! Try again.”
   - Else if `guess` > `number_in_mind`  
     → Display: “Too high! Try again.”
   - Else (`guess` == `number_in_mind`)  
     → Display: " Congratulations! You guessed the correct number.”  
     → Exit the loop
 End