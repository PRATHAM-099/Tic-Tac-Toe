## Tic-Tac-Toe

<div align="center">
  <img src="https://github.com/PRATHAM-099/Tic-Tac-Toe/blob/main/Resources/FinalWin.gif" alt="Tic Tac Toe" />
</div>

This is a Player vs Player Tic Tac Toe game using C# programming language. 
It allows users to play total 5 rounds. 
This is a 2 Player game and players has to choose their respective symbols before playing.

## Files & DIRECTORIES
- <a href="https://github.com/PRATHAM-099/Tic-Tac-Toe/blob/main/TicTacToe.sln">TicTacToe.sln</a> : A text-based file that contains information about the project environment, state, and name-value parameters. This is a structure file used for organizing this project in Microsoft Visual Studio.
- <a href="https://github.com/PRATHAM-099/Tic-Tac-Toe/blob/main/TicTacToe/Tic-Tac-Toe.cs">Tic-Tac-Toe.cs</a> : The file that contains the source code of the whole project.
- <a href="https://github.com/PRATHAM-099/Tic-Tac-Toe/blob/main/TicTacToe/Tic-Tac-Toe.Designer.cs">Tic-Tac-Toe.Designer.cs</a> : The designer file has the code automatically generated by the designer to hold the form’s layout information that was created using the Visual Studio IDE.
- <a href="https://github.com/PRATHAM-099/Tic-Tac-Toe/tree/main/Tic-Tac-Toe%20Setup">Setup</a> : The "Setup" directory is constaining files that are used to create an installation package for this application, they can be used to distribute the project to end-users.
- <a href="https://github.com/PRATHAM-099/Tic-Tac-Toe/tree/main/Tic-Tac-Toe%20Setup/Debug">setup.exe</a> : An executable file (EXE file) that is containing an encoded sequence of instructions that the system can execute directly when the user will click the file icon. 

## Source Code
- <a href="https://github.com/PRATHAM-099/Tic-Tac-Toe/blob/main/TicTacToe/Tic-Tac-Toe.cs">Tic-Tac-Toe.cs</a> has the source code for performing the Tic Tac Toe game in C#. It defines a 2D array of buttons to represent the game board and initializes the game board by assigning each button to its corresponding button on the form. It also declares variables to keep track of the game state, including the number of rounds played, the number of buttons clicked, the current player symbol (X or O), and the number of wins for each player.
- The ***turn_decider()*** function determines which player's turn it is based on the number of buttons clicked so far.
- The game board has event handlers for each button to handle the button click event. When a button is clicked, the ***turn_decider()*** function is called to determine the current player's symbol, and the symbol is displayed on the button and the buttons are then disabled.
- If the number of buttons clicked is greater than or equal to 5, the ***check_winner()*** function is called to check if there is a winner for the round.
- The ***check_winner()*** function checks if there is a winner for the current round by checking each row, column, and diagonal of the game board. If there is a winner, a message is displayed, the win count for the corresponding player is incremented.
- The ***necessary_calculations()*** function is called to update the score.
- The ***clear()*** function is also called to reset the game board for the next round.

## Design
<div align="center">
  <img src="https://github.com/PRATHAM-099/Tic-Tac-Toe/blob/main/Resources/pic.png" alt="Tic Tac Toe" />
</div>

- The design has several buttons, labels.
- The buttons are used to create a Tic Tac Toe game board.
- The labels will display information such as the current round number and the scores for player O and player X.


## Functionality
<div align="center">
  <img src="https://github.com/PRATHAM-099/Tic-Tac-Toe/blob/main/Resources/OWin.gif" alt="Tic Tac Toe" height="250" width="350"/> 
  <img src="https://github.com/PRATHAM-099/Tic-Tac-Toe/blob/main/Resources/XWin.gif" alt="Tic Tac Toe" height="250" width="350"/> 
  <img src="https://github.com/PRATHAM-099/Tic-Tac-Toe/blob/main/Resources/Draw.gif" alt="Tic Tac Toe" height="250" width="350"/>
</div>

- Each player selects their respective symbols to play.
- Whenever the X wins or O wins, winning message of the resposible player is displayed and their score is incremented. In the event of draw, the message for a draw match is displayed and their is no increment in the score of any player.
- If Both the player has same score even after 5 rounds a super round is played to dermine the winner.

## Installation
Here are the steps to install and run the Tic-Tac-Toe game from this GitHub repository
- Go to the GitHub repository at https://github.com/PRATHAM-099/Tic-Tac-Toe
- Click on the green "Code" button and select "Download ZIP" to download the code as a zip file.
- Extract the contents of the downloaded zip file to a folder on your computer.
- Open a command prompt or terminal window and navigate to the extracted folder using the "cd" command.
- Once you are inside the project folder, you will find a file named "tic_tac_toe.exe". This is the executable file that you need to run to play the game.
- Run the executable file by typing "tic_tac_toe.exe" in the command prompt or terminal window and pressing Enter.
- The Tic-Tac-Toe game will now start. Follow the on-screen instructions to play the game.
- That's it! You have successfully installed and run the Tic-Tac-Toe game.
