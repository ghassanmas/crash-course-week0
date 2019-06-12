# Calculator Assignment

### Requirements
* Build a calculator that can add, subtract, multiply and divide.
* Add all the event listeners using javascript (**do not use onClick in the html**)
* Users should be able to string together several operations and get the right answer: 12 + 7 - 5 * 3 etc.
* You should make sure long numbers don’t overflow the screen.
* Pressing “clear” should wipe out any existing data.
* Host it on github pages.

### Stretch goals
* Add a '.' button and let users input decimals! Make sure you don’t let them type more than one though: 12.3.56.5. (disable the decimal button if there’s already one in the display)
* Add a “backspace” button, so the user can undo if they click the wrong number.
* Make it look nice!
* Refactor your code:
    - aim to have code that doesnt repeat itself (may will need to use a loop)
    - if you are using a loop try not to use a for loop (there is always a more efficient loop to use! research which one would be best for your use case)


### Suggested steps

1. Create a basic HTML calculator with buttons for each digit, each of the above functions, an “Equals” key, a display screen and a “clear” button.

2. Make the display screen show the numbers and operators you have pressed so far e.g. "5+71". you should be storing the ‘display value’ in a variable somewhere for use in the next step.

3. Make the calculator work! You’ll need to store the first number that is input into the calculator when a user presses an operator, and also save which operation has been chosen and then use the function you created to calculate the answer when the user presses the “=” key.

**hint: look at the eval() function**
