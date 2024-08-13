# Brodys Portfolio

Welcome!
This repository showcases two of my group projects: a **Banking App** and a **Hangman Game** as well as 
a few other projects I created. These projects are to show case what I have learned throughout my software engineering class 
and the journey. Enjoy. 

## Table of Contents

1. [Banking App](#banking-app)
2. [Hangman Game](#hangman-game)
3. [Connect Four](#Connect-Four)
4. [Read Write Text File](#Read-Write)
5. [Web Form](#Web-Form)
6. [Technologies Used](#technologies-used)
7. [Installation](#installation)
8. [Contact](#contact)

## Banking App
-  [Banking](https://github.com/Weber-Cooper-Maitoza/banking-app-group)
### Overview
The Banking App allows users to manage their finances with ease. It includes features such as:
- Viewing account balances.
- Making deposits withdrawals and transfers.
- Admin accounts, employee acounts, and customers.
- Login and create account pages.

### Features
- **User Authentication:** Secure login and session management to protect user data.
- **Password Hashing:** Storing obscure passwords inside the database for protection
- **Account Management:** View and manage checking, savings, and investment accounts.
- **Transaction History:** Track deposits, withdraws and transfers for each user.

### Contributions 
- Password hashing 
- Create Account front / back  
- Login front / back 
- Create Admin account front / back 
- Creating Sessions
- Holding an employees or admin status with a customer id in session for employee access to customers account

### Technologies
- Frontend: React
- Backend: Express.js
- Database: MongoDB

 ![Hangman Demo](gifs/bankDemo.gif)

### How to Run
1. Clone the repository.
2. Navigate to the `banking-app-group` directory.
3. Run `npm install` to install dependencies on front and back end.
4. Start the development server with `npm start` on both ends.

## Hangman Game
-  [Hangman](https://github.com/Weber-Cooper-Maitoza/Hangman_Game_Group)

### Overview
Classic word guessing game where players try to guess the word before running out of attempts.
A highscore is kept for the players and displays when a game is won or lost. 

### Features
- **Interactive Gameplay:** Users can guess letters and see the correct and incorrect letters while displaying where correct guesses are made.
- **Score Tracking:** Keeps track of high scores for each length of word

### Contributions
- Selecting random word from database.
- Creating session to keep username, word, length, letters guessed, and if guess was in word.
- Checking users guessed letter and returning array with only correct guesses shown.
- Backend route returning correct word.

### Technologies
- Backend: Node.js with Express.js for session management
- Frontend: HTML, CSS, JavaScript

![Hangman Demo](gifs/hangmanDemo.gif)

### How to Run
1. Clone the repository.
2. Navigate to the `Hangman-Game-Group` directory.
3. Run `npm install` to install dependencies on both ends.
4. Start the development server with `npm start` on both ends.


## Connect Four

-  [Connect Four](https://github.com/BrodyGGG/connectFour/tree/main/connectFour)

### Overview
-React web application for the classic connect four game 

### Features
- Two players
- Winning and tying moves 
- Displays players turn and winner
- Tiles "fall" until landing on block or bottom row
- Bad color choices (:

### Technologies
- Frontend: React
- Javascript

### How to Run
1. Clone the repository.
2. Navigate to the `connectFour` directory.
3. Run `npm install` to install dependencies.
4. Start the development server with `npm start`.

   
## Read Write

-  [Read Write](https://github.com/BrodyGGG/readWriteTextfile)

### Overview
- Saving data to a local text file.
- User saves there name and favorite food.
- Search a food to see if anyone else loves that food 

### Features
- Express
- Front and backend routes
- Handling parameters 

### Technologies
- HTML
- Javascript
- Express

### How to Run
1. Clone the repository.
2. Navigate to the `readWrite` directory.
3. Run `npm install` to install dependencies.
4. Start the development server with `npm start`.

## Web Form

-  [Web Form](https://github.com/BrodyGGG/simpleReactWebForm)

### Overview
- Saving data to a local text file.
- User saves there name and favorite food.

### Features
- Express
- Front and backend routes 

### Technologies
- HTML
- Javascript
- Express

### How to Run
1. Clone the repository.
2. Navigate to the `webForm` directory.
3. Run `npm install` to install dependencies.
4. Start the development server with `npm start`.


## Technologies Used

- **Frontend:** React, HTML, CSS, JavaScript
- **Backend:** Node.js, Express.js
- **Database:** MongoDB

## Installation

To set up the projects locally:
1. Clone this repository:
   git clone https://github.com/BrodyGGG/BrodyGGG.github.io
   
## Contact 
-**Email:** brodygardner@mail.weber.edu
-**Github:** [BrodyGGG](https://github.com/BrodyGGG)
