# Team-Profile-Generator

To build a Node.js command-line application that takes in information about employees 
on a software engineering team and generates an HTML webpage that displays summaries for each person.

In the application we are using Jest (https://www.npmjs.com/package/jest)  
for running the unit tests and Inquirer (https://www.npmjs.com/package/inquirer)  
for collecting input from the user. 

The application will be invoked by using the following command:

node index.js

To make a walkthrough video that demonstrates its functionality and all of the tests passing. 

# Output Screenshot

<img src="./assets/screenshot.png">

# User Story

AS A manager
I WANT to generate a webpage that displays my team's basic info
SO THAT I have quick access to their emails and GitHub profiles

#Acceptance Criteria

GIVEN a command-line application that accepts user input
WHEN I am prompted for my team members and their information
THEN an HTML file is generated that displays a nicely formatted team roster based on user input
WHEN I click on an email address in the HTML
THEN my default email program opens and populates the TO field of the email with the address
WHEN I click on the GitHub username
THEN that GitHub profile opens in a new tab
WHEN I start the application
THEN I am prompted to enter the team manager’s name, employee ID, email address, and office number
WHEN I enter the team manager’s name, employee ID, email address, and office number
THEN I am presented with a menu with the option to add an engineer or an intern or to finish building my team
WHEN I select the engineer option
THEN I am prompted to enter the engineer’s name, ID, email, and GitHub username, and I am taken back to the menu
WHEN I select the intern option
THEN I am prompted to enter the intern’s name, ID, email, and school, and I am taken back to the menu
WHEN I decide to finish building my team
THEN I exit the application, and the HTML is generated

## Live demo link

https://www.awesomescreenshot.com/video/11166975?key=d1e0b64117c583cd635a0de46f6e8783
