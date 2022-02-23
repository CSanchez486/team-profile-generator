# Team Profile Generator

Team Profile Generator is a node.js command line application that creates an HTML page when basic information for team members is added to the prompt.

## Installation
```
npm install
```
## Usage
The application will be invoked by using the following command:
```
node index.js

## User Story

Users will be able to generate a team profile by providing teams basic information.

## Acceptance Criteria

```md
1. GIVEN a command-line application that accepts user input when I am prompted for my team members and their information
2. THEN an HTML file is generated that displays a nicely formatted team roster based on user input when I click on an email address in the HTML
3. THEN my default email program opens and populates the TO field of the email with the address when I click on the GitHub username
4. THEN that GitHub profile opens in a new tab when I start the application
5. THEN I am prompted to enter the team manager’s name, employee ID, email address, and office number
when I enter the team manager’s name, employee ID, email address, and office number
6. THEN I am presented with a menu with the option to add an engineer or an intern or to finish building my team when I select the engineer option
7. THEN I am prompted to enter the engineer’s name, ID, email, and GitHub username, and I am taken back to the menu when I select the intern option
8. THEN I am prompted to enter the intern’s name, ID, email, and school, and I am taken back to the menu when I decide to finish building my team
9. THEN I exit the application, and the HTML is generated
```