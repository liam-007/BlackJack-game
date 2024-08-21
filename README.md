Black Jack Java Game
Overview
This is a simple Black Jack game written in Java using Swing for the graphical user interface. Players compete against a computer dealer to get as close to 21 as possible without going over.

Features
•	Graphical Interface: Displays cards and game status using Java Swing.
•	Deck Management: Standard 52-card deck, shuffled and dealt randomly.
•	Gameplay Actions: Hit to draw more cards or stay to hold your hand.
•	Outcome Display: Shows results as "You Win!", "You Lose!", or "Tie!".

Requirements
•	Java Development Kit (JDK) 8 or later.
•	Card images in the ./cards/ directory.

Setup Instructions
Using Visual Studio Code
1.	Clone or Download the Repository
Clone the repo with: git clone https://github.com/liam-007/BlackJack-game.git
Or download the project files from GitHub.
2.	Open the Project
-	Open Visual Studio Code.
-	Go to File > Open Folder and select the project directory.
3.	Install Java Extensions
-	Install the Java Extension Pack from the Extensions view.
4.	Prepare Card Images
Place card images in the ./cards/ directory with filenames like <value>-<type>.png (e.g., A-C.png for Ace of Clubs).
5.	Compile and Run
-	Open the terminal in Visual Studio Code.
-	Compile the code with: javac App.java BlackJack.java
-	Run the game with: java App

Using Other IDEs
1.	Import the Project
Import the project into your IDE (e.g., IntelliJ IDEA, Eclipse).
2.	Prepare Card Images
Ensure images are in the ./cards/ directory with the correct filenames.
3.	Build and Run
Use your IDE’s build and run features to start the game.

Gameplay
•	Hit: Click "Hit" to draw an additional card.
•	Stay: Click "Stay" to hold your hand.
•	Result: The game will show whether you win, lose, or tie.

Code Overview
•	Card Class: Represents a card with its value and suit.
•	Black Jack Class: Handles game logic and UI updates.
•	App Class: Starts the game.

Issues
•	Card Images: Make sure image paths and filenames are correct.

Contributing
To contribute, fork the repo and submit a pull request.

Contact
For questions or feedback, contact [liamcole0705@gmail.com].
