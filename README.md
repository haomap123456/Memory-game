# Memory-game
[![forthebadge](https://forthebadge.com/images/badges/uses-html.svg)](https://forthebadge.com)   [![forthebadge](https://forthebadge.com/images/badges/uses-css.svg)](https://forthebadge.com)  [![forthebadge](https://forthebadge.com/images/badges/made-with-javascript.svg)](https://forthebadge.com)

The Memory Game Project is made from HTML, CSS,and JavaScript. This is a memory game that requires you to have a high memory capacity in order to find the pairs in the shortest possible time and least amount of turns.


## Description
The game board consists of sixteen cards which are arranged randomly in the board and they are divided into 8 different pairs. The game is very simple, in each round you flip the two cards and find two identical cards until the entire board is overturned.

![Matching Game](https://camo.githubusercontent.com/62bfca8e77f922085615c2304f324f448d691c5c/68747470733a2f2f64313768323774366835313561352e636c6f756466726f6e742e6e65742f746f706865722f323031372f46656272756172792f35383962623937325f73637265656e2d73686f742d323031372d30322d30372d61742d332e30332e31352d706d2f73637265656e2d73686f742d323031372d30322d30372d61742d332e30332e31352d706d2e706e67)

## How to play  


1. Click a card to flip it over. The timer starts and moves begin to count.
2. Click a second card to flip it over.
3. If the two cards match, both cards will change to green and stay open.
4. If the two cards do not match , both cards are flipped face down (black).
5. Players will flip the cards until they find the 8 matches on the game board. The game will announce the winner after all the cards are flipped over.

## Picture in game
1. ### Matched cards.
    - ![capture](https://user-images.githubusercontent.com/37636748/38788205-19a982f6-40f8-11e8-8974-5ed9267dd51a.PNG).
2. ### Reset button (yellow highlight).
    - ![capture reset](https://user-images.githubusercontent.com/37636748/38788358-e06aed12-40f8-11e8-8b20-a7e0f3cb0349.PNG).
3. ### Moves count (yellow highlight).
    - ![capture move](https://user-images.githubusercontent.com/37636748/38788388-048cf104-40f9-11e8-922b-3b7a66bd7155.PNG).
4. ### Victory.
    - ![capture victory](https://user-images.githubusercontent.com/37636748/38788426-30855346-40f9-11e8-8cd2-01c578d5f996.PNG).
## Issue
1. Player are able to click 3 cards at once . However, the system automatically compares the two cards that are opened first. I also fixed this by using setTimeOut() function and reducing the timeout when opening the card.
2. There is still a problem with my game that players can pick up the overturned items and cause game errors.
## Author
* HO HOAN HAO

