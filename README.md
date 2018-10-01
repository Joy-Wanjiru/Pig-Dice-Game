# **PIG DICE GAME**

## AUTHOR: *Muhia Joy Wanjiru*


## PROJECT DESCRIPTION:
Each turn, a player repeatedly rolls a dice until either a 1 is rolled or the player decides to "hold":

If the player rolls a 1, they score nothing and it becomes the next player's turn.
If the player rolls any other number, it is added to their turn total and the player's turn continues.
If a player chooses to "hold", their turn total is added to their score, and it becomes the next player's turn.

The first player to score 100 or more points wins.
(source: https://en.wikipedia.org/wiki/Pig_(dice_game))

## SETUP INSTRUCTIONS:
Clone to your local machine using: git clone https://github.com/Joy-Wanjiru/Quiz-Board/tree/gh-pages

## TECHNOLOGIES USED:
JavaScript
HTML
CSS
Bootstrap
jQuery

## BEHAVIOR DRIVEN DEVELOPMENT:
DESCRIPTION | INPUT | OUTPUT
------------|-------|-------
When player rolls dice | Click Roll Dice button | Random number is shown as Current Roll
When player wants to roll again | Click Roll Dice button | Random number is shown as Current Roll and Cumulative Score shows the current + previous scores
When player wants to end turn | Click End Turn button | The current player's turn ends and the other player's turn begins
When player rolls >=6 | Random number after rolling is >=6 | Cumulative score increases by the current roll value and the player can choose to keep playing
When player rolls a 1 | Random number after rolling dice is 1 | The cumulative score becomes "0"
When either players score is >=100 | Cumulative score after rolling is >=100 | Current player wins the game

LIVE LINK:
Visit the website at: https://joy-wanjiru.github.io/Pig-Dice-Game/

LICENSE:
The MIT License

Copyright (c) 2010-2018 Google, Inc. http://angularjs.org

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
