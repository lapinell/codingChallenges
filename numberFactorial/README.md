
# Number Factorial Challenge
by [CodeByte](https://coderbyte.com/editor/guest:First%20Factorial:JavaScript)

Tags: recursion, math fundamentals | Difficulty: Easy

## Challenge

Using the JavaScript language, have the function FirstFactorial(num) take the num parameter being passed and return the factorial of it (e.g. if num = 4, return (4 * 3 * 2 * 1)). For the test cases, the range will be between 1 and 18 and the input will always be an integer. 

### Sample Test Cases

Input: 4 -> Output: 24

Input: 8 -> Output: 40320

## Thought Process

Using vanilla javascript/ES6:

1. User will enter a number between 1 and 18 into the input field and press submit
2. A function will get the input value and generate the remaining numbers
3. It will then multiply all the numbers together and retun the value
4. Then it will output: 
    * The number and it's factorials
    * The value of the factorials

## Design Methodology

**Design Goals**
 - easy for the user to understand what the page is used for
 - intuitive for the user to use

**Stretch Goals**
 - the user can see a list of previous inputs and outputs that they have completed in the current session
 - the user can choose to save their inputs and outputs (using local storage) for use in the next session
 - user can choose to clear their stored inputs and outputs