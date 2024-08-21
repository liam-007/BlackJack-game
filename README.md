Black Jack Java Game

Overview
This Java application implements a simple Black Jack game with a graphical user interface (GUI) using Swing. 
Players compete against a computer dealer, aiming to get as close to 21 as possible without exceeding it. 
The game supports basic actions such as hitting and staying, and displays the result based on the final hands.

Features
•	Graphical User Interface: Created using Java Swing to display cards and game status.
•	Deck Management: Standard 52-card deck is shuffled and dealt randomly.
•	Gameplay Actions: Players can choose to hit or stay. The dealer plays automatically based on standard rules.
•	Outcome Display: Results are shown as "You Win!", "You Lose!", or "Tie!".

Requirements
•	Java Development Kit (JDK) 8 or later.
•	Card images located in the ./cards/ directory.
Setup Instructions

Using Visual Studio Code
1.Clone or Download the Repository
If you have Git installed, you can clone the repository using:
git clone https://github.com/username/repository.git
Alternatively, download the project files from GitHub and extract them to a local directory.

2.Open the Project in Visual Studio Code
- Open Visual Studio Code.
- Go to File > Open Folder... and select the directory where you extracted or cloned the project.

3.Install Java Extension Pack
- Install the Java Extension Pack from the Extensions view in Visual Studio Code to support Java development.
- The extension pack includes necessary tools like the Language Support for Java(TM) by Red Hat, Debugger for Java, and Maven for Java.

4.Prepare Card Images
Ensure you have card images in the ./cards/ directory. Each image should be named using the format <value>-<type>.png (e.g., A-C.png for the Ace of Clubs).

5.Compile and Run the Project
- Open the terminal in Visual Studio Code by selecting Terminal > New Terminal.
- Compile the Java files using: javac App.java BlackJack.java
- Run the game with: java App

Using Another IDE
1.Import the Project
Import the project into your preferred Java IDE (e.g., IntelliJ IDEA, Eclipse):
- Open your IDE and use the import or open project functionality to select the directory containing the Java files.

2.Prepare Card Images
Make sure card images are in the ./cards/ directory, named as <value>-<type>.png.

3.Build and Run the Project
Use your IDE’s build and run tools to compile and execute the App class. Typically, you would:
- Build the project using the IDE’s build command.
- Run the App class to start the game.

Gameplay Instructions
•	Hit: Click the "Hit" button to draw an additional card.
•	Stay: Click the "Stay" button to hold your current hand.
•	Game Result: The game will display a message indicating whether you won, lost, or tied based on the final hands.

Code Overview
•	Card Class: Defines a card with a value and suit, and provides methods for determining its value and image path.
•	BlackJack Class: Contains game logic, including deck management, dealing cards, and updating the GUI.
•	App Class: Entry point of the application, responsible for initializing and starting the BlackJack game.

Known Issues
•	Card Image Path: Verify that card images are correctly placed in the ./cards/ directory and that paths are accurate.

Contributing
If you would like to contribute to this project, please fork the repository and submit a pull request with your changes or improvements.
Contact

For questions or feedback, please contact liamcole0705@gmail.com.
