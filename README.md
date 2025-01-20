# Python-14-Day-Challenge

The following is a description of the project associated with Kevin Markham of Data School. If you'd like to learn more about Data School and the courses available, visit his site, https://www.dataschool.io/start/. 

Steps
1. Create the grid:
  Create a square grid of any size (4x4, for example).
  Represent the grid internally using a list of lists (not an array).

2. Set locations for the player and treasure:
  Set random locations on the grid for both the player and the treasure.
  Ensure that the player and treasure are not at the same location.

3. Run the game loop until the player finds the treasure:
  Print the grid to show the current location of the player (but not the treasure).
  Allow the player to input a direction, ask for a hint, or exit the game:
    If they input a direction ("up", "down", "left", "right"), move the player one spot in that direction, unless that would take them outside of the grid boundary (in which case an error message should be printed).
    If they input "hint", tell the player how many moves it would take to reach the treasure from their current location.
    If they input "exit", end the game.
    If they input any other string, print an error message.

4. Once the player finds the treasure:
  Tell the player how many moves it took to win, and how many hints they used.
  Then, end the game.

Guidelines
  Use meaningful object names.
  Use functions to organize the code.
  Write docstrings for all functions.
  Test many different scenarios to make sure the game always works as expected.

Hints
This project will require that you use a few Python functions and features that I did not teach in the course. You can view a short Python script that I created to demonstrate these functions. Or, if you want more of a challenge, don't look at the script and instead discover these functions on your own!

Adjusting the level of difficulty
If the project is too challenging, you can simplify the requirements in one or more of the following ways:
  Instead of allowing the user to define the grid size, use a fixed grid size.
  Instead of placing the player and treasure at random locations, place them at fixed locations.
  Instead of checking the grid boundary, trust that the player will not go outside of the grid boundary.
  Don't allow the user to ask for hints.
If the project is not challenging enough, you can add complexity in one or more of the following ways:
  Allow for a non-square grid.
  Add a timer to keep track of how long the player takes to find the treasure.
  Place obstacles at random spots in the grid that the player needs to navigate around.
  Place traps at random spots in the grid that send the player back to their starting position.
  Allow for multiple treasures.
  Add an enemy player controlled by the computer. They are also searching for the treasure, and the player must find it first.
