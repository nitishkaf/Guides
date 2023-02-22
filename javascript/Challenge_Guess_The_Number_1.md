# Challenge - Guess The Number

## Instructions:

Write a JavaScript program that generates a random number between 1 and 10 (inclusive). The program should then prompt the user to guess the number. If the user's guess is correct, the program should display a message saying "Congratulations! You guessed the number!". If the user's guess is incorrect, the program should display a message saying "Sorry, try again!" and allow the user to guess again.

## Expected Results:

After running the program, the user should be prompted to guess the number. If the user guesses correctly, the program should display a message saying "Congratulations! You guessed the number!". If the user guesses incorrectly, the program should display a message saying "Sorry, try again!" and allow the user to guess again.

```jsx
// Generate a random number between 1 and 10

// Prompt the user to guess the number

// Loop until the user guesses the correct number

  // If the guess is incorrect, let the user try again


  // If the user clicks "cancel" or enters an invalid input, exit the loop


// If the user guessed the number, congratulate them

```

## Hints:

1. Use the `Math.random()` function to generate a random number.
2. Use the `prompt()` function to get input from the user.
3. Use a while loop to allow the user to guess multiple times until they guess correctly.
4. Use an `if` statement to check if the user's guess is correct.
5. Use `console.log()` to display messages to the user.

Good luck and have fun!

<details>
  <summary>Click For Solution</summary>


```js
// Generate a random number between 1 and 10
const randomNumber = Math.floor(Math.random() * 10) + 1;

// Prompt the user to guess the number
let guess = prompt("Guess the number between 1 and 10");

// Loop until the user guesses the correct number
while (guess != randomNumber) {
  // If the guess is incorrect, let the user try again
  guess = prompt("Sorry, try again!");

  // If the user clicks "cancel" or enters an invalid input, exit the loop
  if (guess === null || isNaN(guess)) {
    break;
  }
}

// If the user guessed the number, congratulate them
if (guess == randomNumber) {
  console.log("Congratulations! You guessed the number!");
} else {
  console.log("Sorry, better luck next time!");
}
```

</details>
