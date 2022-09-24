## Timed Quiz
https://shaynekaruna.github.io/TimedQuiz/

## Acceptance Criteria

```
GIVEN I am taking a code quiz
WHEN I click the start button
THEN a timer starts and I am presented with a question
WHEN I answer a question
THEN I am presented with another question
WHEN I answer a question incorrectly
THEN time is subtracted from the clock
WHEN all questions are answered or the timer reaches 0
THEN the game is over
WHEN the game is over
THEN I can save my initials and my score
``` 

## The Process
To satisfy our client's needs, we had to:
- Create two HTML files (one to take quiz and one to view scores)
- Create two JavaScript files (one containing functions to execute the quiz and one to store previous scores)
- Modify HTML file to dynamically work with JavaScript file


Specific functions in JavaScript file

```
- Variable listing all prompt, options, and answer
- Get elements from DOM (questions, timer, options, submit button, start button, restart button, name and feedback)
- Variable setting quiz's initial state
- Function starting uqiz
- Function looping through array of question and answers and create list with buttons
- Function checking for right answers and deduct time for wrong answer, proceed to next question
- Function ending quiz, stop timer and show final score
- Function ending quiz if timer reaches 0 
- Function saving score in local storage along with users' name
```

Specific functions in Highscore JavaScript file

```
- Get score button element from DOM 
- Rank previous scores in order by retrieving scores from localStorage
- Clear previous scores when users click clear
```

Shayne Karunakaran
