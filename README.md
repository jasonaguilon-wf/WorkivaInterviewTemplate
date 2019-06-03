This boilerplate is built using [create-react-app](https://github.com/facebook/create-react-app) so you will want to read the User Guide for more goodies.

Use `npm install` to build. Followed by `npm start` to run the application.

## App Info

This is the start of a basic message logging application that allows message submission and printing capabilities.

The initial state of the application is that a user can submit a message in the left half of the screen and see the message on the right half.

## Improvement Tasks

- Ignore messages that are duplicates.
- When a user submits the message include the time at which it was submitted in the output on the right half of the screen.
- Allow a user to include a display name to be rendered along side the message on the right half of the screen.
  - The submit button should be disabled until both the name and the message are populated.
- Allow a user to edit any message by clicking on the message in the right half of the screen and rendering it in the input area on the left. The user can then edit the message or display name and resubmit the message. The updated message is then displayed in the same position on the right half of the screen.
  - BONUS: Show an edit icon in the right hand panel after a message has been updated.
