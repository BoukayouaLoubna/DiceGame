# DiceGame

# Dice Game : Servlets, Session Management, Context, and Filters

This project involves a game where three dice are rolled one by one in any order through an interface like the one described in Figure 1. These dice are numbered 1, 2, and 3. The text field allows the user to input the number of the die to roll, and rolling the die is triggered by the "Roll the Die" button. During a game session, the same die should not be rolled more than once. If a player rolls the same die more than once, the game stops, and the player receives a score of -1.

If the result obtained for die number 1 is strictly less than the result obtained for die number 2, and the result obtained for die number 2 is strictly less than the result obtained for die number 3, then the player receives a score equal to the sum of the results obtained for all 3 dice. Otherwise, the player receives a score of 0. The application should stop the game session as soon as the score can be determined. For example, if we get 6 for die number 1, there is no need to wait for the results of the other dice; the score in this case is 0.

A game session ends either after rolling all 3 dice, due to an error in rolling the same die twice, or because the condition "result (die 1) < result (die 2) < result (die 3)" cannot possibly be true (e.g., getting 6 for the first die).

At the end of a game session, the application displays the score of the game that was just played and the highest score recorded in the application.

This application does not use a database but simply stores data in appropriate data structures within the application context.

## Features to Implement:

- Users should be able to create an account.
- The application stores user information (name, surname, login, password, and best score).
- The application allows the user to:
  - Log in / Log out
  - Play the game
  - Check their best score
  - Check the best scores of other players

---

## Installation

To run this application locally, ensure you have Java and a Servlet container (e.g., Apache Tomcat) installed on your system.

1. Clone this repository:
   ```bash
   git clone https://github.com/BoukayouaLoubna/DiceGame.git

 2. Deploy the application on your Servlet container.

 3. Access the application through your web browser at `kogintest` servlet at [http://localhost:8080/kogintest](http://localhost:8080/kogintest).


## Contact
For any inquiries or feedback, please contact loubnaboukayoua@gmail or samiha.elmansouri@etu.uae.ac.ma

