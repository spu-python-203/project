# Projects

- [Projects](#projects)
  - [Rolling dice](#rolling-dice)
  - [Tic tac toe](#tic-tac-toe)
  - [Quiz app](#quiz-app)
  - [Rock Paper Scissors](#rock-paper-scissors)
  - [Hangman](#hangman)
  - [Typing speed test](#typing-speed-test)
  - [To do list](#to-do-list)
  - [Passwords manager](#passwords-manager)
  - [Magic Ball](#magic-ball)
  - [Book store project](#book-store-project)
  
## Rolling dice

```
> How many dies do you want?
3
> Dice is rolled, and the multiplication of numbers stored. Can you guess?
```

**Description**

Roll a dice. Let user guess the number.

**Objectives**

- Pick a number from # of dices. There can be more than 1 die, and user can select!
- Print a message about the game. And let user know that a number is picked.
- Ask user for an input.
- Print out a message if user needs to guess higher or lower next time.
- Count number of guesses and print this at the end of the game.

## Tic tac toe

```
X| |
-+-+-
 | |
-+-+-
 | |

> Played, now it is your turn, where to?
```

**Description**

Make a tic tac toe game where you have to draw a board, and play tic tac toe game. The goal is to match 3 `X`s or `O`s horizontally, vertically, or diagonally. You can make this against computer, 2 player game, or computer against computer.

**Objectives**

- Draw a board, print message to user to make a move
- Ask input from user
- Check if any of the player has a winning shape
- if there are no places left ano no one win, restart the game.

## Quiz app

```
> Pick a category, and # of questions.
Math, 4
> How many edges does a triangle has?
```

**Description**

Quiz people based on questions on categories! User picks category, and number of questions, your app asks them questions on this category. User gets a score out of 100 based on true answers!

**Objectives**

- Make a set of questions on at least 3 different categories. Record answers to the questions as well.
- Ask user an input for category, and the number of questions
- Print random questions from your dataset, and ask user for an input
- compare users answer and the truth, if correct give user point. 
- Score user results at the end of the game based on the number of questions.

## Rock Paper Scissors

```
> Rock wins against scissors, paper wins against rock, scissors wins agains paper!
> Rock, Paper, or Scissors? 
```

**Description**

Make rock paper scissors game one can win based on he choise of rock, paper or scissors. Rock wins against scissors, paper wins against rock, scissors wins agains paper! You can make this against computer, 2 player game, or computer against computer.

**Objectives**

- Print a message about the game, and ask a question of user's choise on options
- Make a random selection if opponent is computer
- Compare both selections against each other, and choose the winner
- Announce winner, and ask if user wants to play again. 
- Game should continue until users exists the game.
  
## Hangman

```
 +---+
 O   |
/|\  |
/ \  |
    ===

> word is _ _ _ _ _
What is next word?
```

**Description**

Draw hangman if user can not guess the word. 

**Objectives**

- Pick a random word from a list of words that you have in a file.
- Draw an initial drawing for the hang, and a placeholder for a word.
- ask a letter from user, and if not in the word, draw hangman!
- if user can not guess until you make the drawing, user lose!

## Typing speed test

```
"Lorem ipsum dolor sit amet, consectetur adipiscing elit, 
sed do eiusmod tempor incididunt ut labore et dolore magna 
aliqua. Ut enim ad minim veniam, quis nostrud exercitation 
ullamco laboris nisi ut aliquip ex ea commodo consequat. "

> type the following text. How fast can you type?
```

**Description**

Measure users typing abilities with time and accuracy!

**Objectives**

- Pick a random text from a file, and print it to user. 
- Ask user to type it as fast as it can. You will measure how long user types, so better to record a time before you start!
- Measure time, and accuracy. Print your results to user. 

<!-- ## Word/ sentence/ counter

```
```

**Description**
**Objectives** -->

## To do list

```
> Welcome to todo list app! Who is using the app?
Harish
> Hi Metin! Here are your options:
 - list todo lists
 - add a new item to a list
 - update existing
 - delete one
> add to grocery: buy milk
added!
> list grocery
[1] milk 
[2] chocolate
[3] banana
-- 3 unmarked, 5 in total.
> mark 2
marked!
> list grocery
[1] milk 
[2] banana
-- 2 unmarked, 5 in total.
```

**Description**

Make a todo app, where user can make todo lists, add items in the list, and mark them as completed.

**Objectives**

- Define a set of categories for todo items.
- Keep a file for each user.
- User should be able to list todo lists, add, update, or delete an item from a list.
- Each list item should have an attribute for being marked, or not.
- Keep record of list items, with dates being added, and marked statuses.
- Make stats for each list.

## Passwords manager

```
> Welcome to passwords mananger! Who is using the app?
Metin
> Hi Metin! Here are your options:
 - list passwords
 - add a new 
 - update existing
 - delete one
 Type the word to do so.
> list
- 01| website 1
    | www.fb.com
    | msenturk 
    | social
- 02| github
    | www.github.com
    | metinsenturk
    | productive 
```

**Description**

Make a passwords manager app where you keep passwords of apps, websites, and anything else.

**Objectives**

- Every password should have a set of attributes, such as name, url, username, password, category, etc.
- Passwords are personal, store each person's password on a differnt file
- App should have 4 commands, list, add, update, delete. 
- You should list passwords, when user wants a list of passwords. Don't print passwords!
- Add should add a new password, where each info can be asked one by one or at once
- Multiple users can use this app, keep a different file for each

<!-- ## Download images from internet

```
```

**Description**
**Objectives** -->

## Magic Ball

```
> Who is playing?
Steve
> Hi Steve!, ask me a question!
> Is Santa real?
> yes

> Who is playing?
Matt
> Hi Matt!, ask me a question!
> Do you think santa is actual person?
> yes
```

**Description**

Make a python app that answers user's questions with yes and no! Your app should get smarter as the person plays more!

**Objectives**

- Make a set of questions that has yes or no answers. Save your results structured.
- Keep a file for each user, with their names.
- Ask user to ask a question, record this answer to user's file.
- Before answering a question:
  - Check if the question is asked before from this user, or any other user, check if there are any similar questions (for example, if a question is similar to any other question, with %80 or higher).
  - If there is a similar one, use that question's answer.
  - If there is no similar match, make a random guess of yes or no.
- Ask user if that was correct or not. Store this value for this question, for this user.
- Keep asking questions until user wants to exit.
- At the end of the game, print every question user asked in that session and guessed answers. Print accuracy of the app as well.


## Book store project

```
> Welcome to book store app. 
> What do you want to do?
    - list
    - rent
    - return
```

**Description**

Make a book store app where books can be rented

**Objectives**

- Make a dataset of books, and keep a set of attributes for each book, such as name, category, availability, etc.
- Print user a message, ask to choose of options:
  - list
  - rent
  - return
- Based on the option print or ask for input. 
  - If it user wants list, list available books.
  - If return, get book name and make the book available.
  - If rent, get the book name and make the book unavailable.
  - If user wants a book that is unavailable, print that accordingly.
- You should also keep a record of who rented which books, when rented and returned.
- You app should also have a function to print stats on popular books, rent durations, etc.
