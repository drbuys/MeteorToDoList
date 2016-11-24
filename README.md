# Meteor To-Do List

## Setup Instructions
This project uses Meteor. You will need to [install Meteor](https://www.meteor.com/install) first.

```zsh
$ git clone https://github.com/drbuys/MeteorToDoList.git
$ cd MeteorToDoList
$ git checkout broken
$ git checkout -b 'ParticipantsName'

$ npm install                   # Install project dependencies
$ npm start                     # Compile and launch
```

## Purpose
- This project is intended to highlight the approach to problem solving of the participant.
- The code is broken, and the errors should give an indication as to where and how to fix the code in order to get the app running again as expected.
- The participant should checkout their own branch from the branch '*broken*' as specified above. The branch '*working*' has the working code in it for comparison

## What is Broken

Removed id="render-target" from div in main.html
Removed App Import from main.jsx
Removed Equality operator from App.jsx line 47
Removed onClick function from the delete button in Task.jsx
Commented out the ref parameter in the input text box
