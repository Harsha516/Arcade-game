# Classic Arcade Game Clone Project

## Table of Contents

-   [Instructions](#instructions)
-   [Contributing](#contributing)

## Instructions

Use this [rubric](https://review.udacity.com/#!/rubrics/15/view) for self-checking your submission.

Make sure the functions you write are **object-oriented** - either class functions (like `Player` and `Enemy`) or class prototype functions such as `Enemy.prototype.checkCollisions`. Also make sure that the keyword `this` is used appropriately within your class and class prototype functions to refer to the object the function is called upon.

Your **README.md** file should be updated with instructions on both how to 1. Run and 2. Play your arcade game.

For detailed instructions on how to get started, check out this [guide](https://docs.google.com/document/d/1v01aScPjSWCCWQLIpFqvg3-vXLH2e8_SZQKC8jNO0Dc/pub?embedded=true).

## Contributing

This repository is the starter code for _all_ Udacity students. Therefore, we most likely will not accept pull requests.

## For details, check out [CONTRIBUTING.md](CONTRIBUTING.md).

## I followed the below steps to complete this game

### Cloning of the project.

-   after reading and verifying the instructions, I got the GitHub link about the skeleton project which was provided by the "UDACITY" in rubric structure.
-   After downloading the files from GitHub, I extracted all the files and observed the structure of the files.
    1\.`css/app.css`
    2\.`img/`
    3\.`js.app.jss`
    4\.`index.html`(root file)
    5\.`README.md`
## Modifications to the CODE

I did the following steps:-

1. Download the skeleton project from GitHub(rubric structure) through link https://github.com/udacity/frontend-nanodegree-arcade-game and run it.
2. Intially when I opened the page, I got the blank page and an error in console panel allEnemies[].
3. Player class also created and variable also assigned.
4. For Actor(Player) I intialised the below functions.
    -`render()`
    -`update()`
    -`handleInput()`
5. `handleInput` is used to handle the input given by player, for this method ,they already implemented some mechanism inorder to I just modified steps to move(in px).
 (a)left arrow :: player to move left side.
 (b)right arrow :: player to move right side.
 (c)up arrow :: player to move up side.
 (d)down arrow :: player to move down side.
6. I used `render()` for placing actor on canvas.
7. I used `update()` to update to update the actor position;updating function is already intialised by parameter(dt).
8. Player will move according to the key directions.
9. When ever we reach top,we need to come back to starting position.
10. I used an array by placing 3 enemies in the game.
11. Move the enemy object in randomly using `math.random()` function.
12. If the actor reaches to the water layer(top of the canvas), then again he/she will get to intial position at where is started addition of score +10.
13. whenever the player collide with enemy--> alert will come.
14. Using "sweet alert"--> score will displayed and TryAgainbutton.
15. When ever we clicked TryAgain button ,game wiil start again.
