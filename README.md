## Calorie Calculator
1. Project Overview

Calorie Calculator is a Java-based console application that calculates a user's Basal Metabolic Rate (BMR) and estimated daily calorie requirement.

The program takes basic details such as gender, age, weight, height, and activity level from the user. Based on these inputs, it performs the required calculations and displays the estimated calorie needs.

The project is designed to practice Java programming concepts such as classes, objects, methods, user input, conditional statements, and basic object-oriented programming.

2. Features
Takes user information through the console
Supports male and female users
Calculates Basal Metabolic Rate (BMR)
Calculates estimated daily calorie requirements
Supports different activity levels:
Sedentary
Moderate
Active
Displays the calculated results clearly
Uses separate classes to handle different parts of the application

3. Technologies / Tools Used
Java
Java Scanner for taking user input
Object-Oriented Programming (OOP)
Visual Studio Code
Git
GitHub

4. Project Structure
Calorie-Calculator/
│
├── CalorieCalculator.java
├── MainApp.java
├── ResultDisplay.java
├── UserData.java
├── UserInputHandler.java
├── .gitignore
└── README.md
File Description
MainApp.java – Contains the main method and starts the application.
UserInputHandler.java – Takes and handles input provided by the user.
UserData.java – Stores the user's details.
CalorieCalculator.java – Contains the logic for calculating BMR and daily calorie requirements.
ResultDisplay.java – Displays the final calculated results.

5. Installation and Running the Project
Prerequisites:
Make sure Java is installed on your computer.
Check the Java version using:java -version
Also check the Java compiler:javac -version

Steps to Run:
Step 1: Clone the repository.
git clone https://github.com/ankitabytes/Calorie-Calculator.git
Step 2: Open the project folder in Visual Studio Code or any Java IDE.

Step 3: Open the terminal inside the project folder.

Step 4: Compile all Java files.
javac *.java
Step 5: Run the main application.
java MainApp

6. Testing Instructions
After running the application, enter the details requested by the program.

Sample Test Case
Gender: F
Age: 20
Weight: 54 kg
Height: 160 cm
Activity Level: active

Sample Input:
Enter your gender (M/F): F
Enter your age (in years): 20
Enter your weight (in kilograms): 54
Enter your height (in centimeters): 160
Enter your activity level (sedentary/moderate/active): active

Expected Output
Your Basal Metabolic Rate (BMR) is: 1356 calories per day.
Your estimated daily calorie needs are: 2339 calories per day.

7. Screenshots

![Calorie Calculator Output](screenshots/output.png)


