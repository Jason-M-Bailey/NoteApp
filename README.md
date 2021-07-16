# 11 Express.js: Note Taker

## Deployed Link:
[Note Taker Deployed on Heroku](https://jasons-note-app.herokuapp.com/notes)

## Your Task

A simple application that can be used to write and save notes. This application uses Express.js back end and will save and retrieve note data from a JSON file and is deployed to Heroku.

## User Story
```
AS A small business owner
I WANT to be able to write and save notes
SO THAT I can organize my thoughts and keep track of tasks I need to complete
```
## Acceptance Criteria
```
GIVEN a note-taking application
WHEN I open the Note Taker
THEN I am presented with a landing page with a link to a notes page 
WHEN I click on the link to the notes page
THEN I am presented with a page with existing notes listed in the left-hand column, plus empty fields to enter a new note title and the note’s text in the right-hand column 
WHEN I enter a new note title and the note’s text
THEN a Save icon appears in the navigation at the top of the page 
WHEN I click on the Save icon
THEN the new note I have entered is saved and appears in the left-hand column with the other existing notes 
WHEN I click on an existing note in the list in the left-hand column
THEN that note appears in the right-hand column 
WHEN I click on the Write icon in the navigation at the top of the page
THEN I am presented with empty fields to enter a new note title and the note’s text in the right-hand column 
```

## Prerequisites
* [NodeJS](https://nodejs.org/)

## Installing

Clone the repository to your local development environment.

```
git clone https://github.com/Jason-M-Bailey/NoteApp.git
```

Navigate to the developer-profile-generator folder using the command prompt.

Run `npm install` to install all dependencies. To use the application locally, run `node server.js` in your Command Line Interface (CLI), and then open `http://localhost:3000` in your preferred browser. The Note Taker app is [live on Heroku](https://jasons-note-app.herokuapp.com/notes) for you to use as well.

## Built With
* [JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
* [NodeJS](https://nodejs.org/)
* Node Packages:
    * [Express](https://www.npmjs.com/package/express)