# Team Profile Generator
This is a software engineering team generator command line application. Using Node CLI, the user can input team member profiles and generate a team profile disply in HTML file.

## User Story
```
AS A user, I want to be able to write and save notes
I WANT to be able to delete notes I've written before
SO THAT I can organize my thoughts and keep track of tasks I need to complete
```

## Functionality

The application will prompt the user for information about the team manager and then information about the team members. 
The user can input any number of team members, and they may be a mix of engineers and interns. 
![Application Screenshot](./assets/workout-tracker-dashboard.png)

When the user has completed building the team, the application will create an HTML file that displays a nicely formatted team roster based on the information provided by the user. 
![Application Screenshot](./assets/workout-tracker-dashboard.png)


## Get Started
Download all files.
Run npm install and node app.js

# Techniques and Technologies Used
The app is run using Node.js using "Inquirer," "FS," and "Jest' node modules. 

This app was created using Object-Oriented Programming concepts, using classes and constructors to create "team member" objects based on information entered by the user. Files for different objects are also stored in separate .js files and passed among one another using module.exports and require.

This app uses concepts from Test-Driven Development. Jest is used to perform tests on all the class constructors to ensure that they behave as expected.  The FS node module is used to generate an HTML file from strings written in JavaScript.