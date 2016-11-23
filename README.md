# Meteor To-Do List

## Setup Instructions
This project uses Meteor. You will need to [install Meteor](https://www.meteor.com/install) first.

```zsh
$ git clone https://github.com/DeloitteDigitalUK/field-agent-demo.git
$ cd field-agent-demo
$ npm install                   # Install project dependencies
$ npm start                     # Compile and launch
```

## Offline Support
This project is intended to highlight the offline capabilities of using Meteor with React. The scenario for this project is a field agent using this web app on their phone. If the field agent loses connection Meteor will allow the user to continue their work offline by utilizing a local [Mongo](https://www.mongodb.com/) instance and then syncing back with the server Mongo once a connection has been reestablished.
