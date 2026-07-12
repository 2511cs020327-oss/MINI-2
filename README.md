# Escape Room Game (Java)

## Objective

This project is a console-based Java game where the player must answer Java programming questions to unlock rooms and escape. The player starts with **3 lives**, and each incorrect answer reduces one life. The game ends when all rooms are completed or all lives are lost.

## Game Flow

### 1. Player Initialization

* Create a player with 3 lives.
* Track the remaining lives throughout the game.
* End the game when no lives remain.

### 2. Room Creation

* Create multiple escape rooms.
* Each room contains:

  * One Java programming question.
  * Four multiple-choice options.
  * One correct answer.

### 3. Main Menu

* Display the game title.
* Show the remaining lives.
* Provide two options:

  * Enter Next Room
  * Exit Game

### 4. Enter Room

* Display the current room question.
* Show all answer choices.
* Accept the player's answer.
* Compare the answer with the correct option.

### 5. Correct Answer

* Unlock the current room.
* Move the player to the next room.
* Continue until all rooms are completed.

### 6. Wrong Answer

* Reduce one life.
* Display the remaining lives.
* Allow the player to try the room again if lives remain.

### 7. Exit Game

* Allow the player to quit the game at any time.
* Display a thank-you message before exiting.

### 8. Game Completion

* If all rooms are completed:

  * Display a Congratulations message.
  * Announce that the player has escaped.

* If all lives are lost:

  * Display Game Over.
  * End the game.

## Technologies Used

* Java
* Object-Oriented Programming (OOP)
* Scanner Class
* Arrays
* Loops
* Conditional Statements
* Methods
* Exception Handling

## Author

Name: S.Hari krishna

Roll Number: 2511CS020327

Department: AIML

Date: 12-07-2026
