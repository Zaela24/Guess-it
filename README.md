# Application Architecture - The UI Layer - Guess It!
This is the toy app for lesson 5 of the [Android App Development in Kotlin course on Udacity](https://www.udacity.com/course/developing-android-apps-with-kotlin--ud9012).

## Guess It!

Guess It is a word guessing app you can play with one or more friends. To play, hold the device in landscape, facing away from you with your thumbs on the **Skip** and **Got It** buttons. Your friends can then give you clues to help you guess the word. 

If you get the word right, press **Got It**. If you're stuck, press **Skip**. The game runs for a minute and then shows you your score.


## Screenshots

![Screenshot 0](screenshots/screen0.png) ![Screenshot 1](screenshots/screen1.png) ![Screenshot 2](screenshots/screen2.png)

## Zaela's Notes

Most of the work I did for this app involved re-organizing the code to properly seperate functionality into dedicated classes.
I also added in a timer to control when the game ends, and implemented in-app phone vibration when the player presses **Got It**, when the timer reaches the last 10 seconds, and when the game is over.
