# g47 Quarter 1 Project: 7 Jumbled Words

## Objective

This project was submitted as my first quarter project for the Galvanize g47 Full Stack Immersive Program. Our task was to create an app or website that fit the following criteria:

* Use valid, semantic HTML
* Use valid, minimally-specific CSS
* Use linted, concise JavaScript
* Use embedded media such as fonts, images, audio or video
* Use a front-end framework such as Bootstrap, Materialize or Foundation
* Respond to form input or user events
* Connect to an external API via AJAX

## Description

This project was inspired by the game [7 Little Words](http://www.7littlewords.com/). At the bottom, there are seven words broken into chunks of 1-3 letters and shuffled. The top is comprised of a bank of seven clues that describe the words at the bottom. The seven clues are generated through an API call to the [Wordnik API](http://developer.wordnik.com/docs.html). Also at the top, the number of letters of each word sits beside each clue.

## Rules

The user must find the word that matches each clue at the top by assembling the tiles at the bottom that make up the word. As they click tiles, the text of the tile is appended to a "guess" bar in the center of the game board.

When the user believes they have correctly formed a word that matches a clue, they can click the "Submit" button. If the guess is correct, it is appended to the small space beside the letter count in the top half of the board. Otherwise, the word is cleared from the guess bar. If the user cannot seem to form any words, he/she can click the "Shuffle" button, which will change the order of the tiles.

When the user has correctly guessed all the words, they are rewarded with a congratulatory message generated using a nifty CSS animation.
