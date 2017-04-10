# Game Project Scope Study

## Required Readings

-   [Game Project](https://github.com/ga-wdi-boston/game-project)
-   [Game API](https://github.com/ga-wdi-boston/game-project-api)
-   [What is a User Story](https://www.mountaingoatsoftware.com/agile/user-stories)

## Deliverables

After reading the `game-project` prompt and the `game-project-api` documentation
please do the following and be prepared to share and discuss during our next
class.

Submit detailed answers to the following in this file via a pull request:

-   A wireframe of what your game project will look like.
https://drive.google.com/drive/folders/0B085YpY7Y_tmZS14UmE5RUg1UEk?usp=sharing

-   The data structure you plan to use.
I plan on basing my data structure on the example API responses provided in the game-project-api repository. Each user will have a username and email address, and will have an id and a token assigned by the API. Each game will also have one or more games associated with the user id and email address, consisting of the X and O inputs, player 1 name and player 2 name.

-   How you will take the markup of the game board and represent it in JS
Each of the 9 tictactoe cells will be buttons in HTML, where each button will have an ID that corresponds to a position in an array created in Javascript. This array will include all 9 buttons, each of which will have an event handler for click events using jQuery. I will also have an array for X and O inputs by both players that will track the buttons that have been clicked so that the game can be reset when evey button has been clicked.

-   How you plan to approach this project.
I plan on following the suggested schedule provided. I will go slowly and methodical, testing my code frequently, bit by bit. Specifically, I will follow the schedule below:
1. Sketch the wireframe (done)
2. Write out user stories (done)
3. Think in user's perspective to make sure the UI is user-friendly, such as by having buttons where they are useful to have, and forms where they're needed. (done)
4. Create a repo on GitHub, and add a README.
5. Create HTML/CSS, and host them on GitHub
6. Create the game logic (JS).
7. Write jQuery code for on click, on submit, and on hover events
8. Use curl to model the backend, then build the backend writing ajax code based on the model.
9. Add extra features if time allows

-   4-8 user stories for your game project.
As a user, I want to sign up and sign in so that I can play the game and keep track of my score.
As a user, I want to input my name and the opponent's name so that the game feels personalized.
As a user, I want to be able to add my input when I click on one of the 9 areas of the board.
As a user, I want to see when I have tied 3 markers in a row.
As a user, I want to see if I won, lost, or tied.
As a user, I want to be able to compete with an opponent.
As a user, I want to be able to reset the game so that I can play a new game.
As a user, I want to be able to log out when I finish playing.

-   How you plan to keep your code modular.
I will have different files/folders for HTML, CSS, and Javascript code, and keep javascript code that have different functionalities in different javascript files. I will use the require and module.exports features in Javascript in order to use functions in one file in another file also.

-   What creative spin will you add to your project?
Sign in and sign up forms will be availble through popups upon clicking sign in or signup buttons. To visually show that a player has tied 3 O's or X's in a row, I will use color effects to highlight the tied markers. Also, I'd like to visually display turns by using color effects on the X and O background. This may all be a bit too ambitious to complete within a week, in which case I may make everything simpler, including the design show in the wireframe. 

-   How will you use version control to backup / track your project?
I will commit early and commit often via git, and write informative commit messages as a way to stay organized.

-   Do you plan to attempt any of the bonuses?
I plan on using hover effects for the buttons on the boards, but nothing more than that for now. I'd like to first satisfying all the requirements. I'll see then if I can add other extra features, such as animations.


You may want to submit pictures for your wireframes and/or user stories.
[Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
has instructions to link to a picture you've uploaded to a service like [Imgur](http://imgur.com/).
