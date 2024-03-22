---
title: Original Game Idea
---

The Peak is a two-player mountain-climbing game inspired by SFU's Burnaby Campus and named for its local newsletter. One player plays as a mountaineer on the mountain, trying to reach the top and score points. The other player plays as the mountain itself, working to hold back the mountaineer with steep cliffs and dangerous hazards!

## Game Core

The game is played with two decks of cards: Goal cards, which determine each player's secret objective in the game, and Mountain cards, which can be played by either player to advance their strategy. It is played on a 7x7 grid with cells that fit a Mountain card. The mountain player puts Mountain cards on the board to create a 2-dimensional "mountain" that the mountaineer moves around on. The mountaineer rolls dice and plays their own Mountain cards to move the Mountaineer Token around the map, picking up each card they successfully land on so they can use its special power later.

## Game Components

### Mountain cards

The main game component is the deck of Mountain cards. Each mountain card has two numbers printed on it: one to represent the Elevation the card gives, and one to represent the Difficulty of climbing it. Each card also has a special power that can be used by the mountaineer to help them overcome obstacles, and some might have passive effects that apply while the card is on the board. For example, a card might allow the mountaineer player to re-roll any die. Another card might penalize the mountaineer if they try to cross the card and fail.

Here are some other possible Mountain cards:
- "Hiking Trail" has low Elevation and Difficulty values and no special abilities, making it easy to cross but worth very little to the mountaineer.
- "Sandstone Cliff" has high Elevation and Difficulty values, and if the mountaineer successfully crosses it they gain the option to switch out their Goal card once.
- "Bear Cave" has low Elevation but high Difficulty, and if the mountaineer fails to cross it the bear chases them to another random spot on the board - however, if they succeed, they get +1 to every die rolled for the rest of the game.

### Goal cards

At the start of the game, each player draws a single Goal card and looks at it. At the end of the game, each player reveals their Goal card and gains extra points if they completed the goal printed on it. Goal cards are symmetrical between both players; for example, the "Conservationist" Goal card might require that the mountaineer stays on trails as much as possible. If the mountaineer player draws this card, they'll gain points for every trail they walk on. If the mountain player draws it, they'll gain points for only allowing the mountaineer to walk on trails.

Here are some other possible Goal cards:
- "Height Seeker" rewards the player for the total height climbed by the mountaineer
- "Hiker" rewards the player for the total number of Mountain cards the mountaineer traverses
- "Naturalist" rewards the player for each safe wildlife encounter

### Other game components

The game also includes a 7x7 board, a Mountaineer Token, and two six-sided dice. The Mountaineer Token is used to keep track of the mountaineer's current position on the board.

## Setup

To set up the game, place the board in the center of the table and put the Mountaineer Token in the middle cell of the board. Each player draws one Goal card and three Mountain cards. Then the game starts and the core loop begins. The mountain player takes the first turn of the game.

## Core Loop

### Mountain player's turn

During their turn, the mountain player can play Mountain cards from their hand by placing them in unoccupied spaces on the board. A space is occupied if it contains either a Mountain card or the Mountaineer Token. Every time the mountain player plays a card, they draw another Mountain card from the deck to replace it.

The mountain player must also make sure that every occupied space on the board is adjacent to at least two other occupied spaces, including the space with the Mountaineer Token. This is to prevent dead ends when the mountaineer is moving around. For example, if the board only contains the Mountaineer Token and a Mountain card, assuming they are adjacent, the mountain player must play at least one more Mountain card next to each of those cells. Then the mountain player must make sure that the new Mountain cards they just played are also adjacent to two or more occupied cells, and so on.

Once the mountain player has played all the cards they want and the connectivity condition is satisfied, the turn passes to the mountaineer player.

### Mountaineer player's turn

The mountaineer player can do either of two things as many times as they like before ending the turn:
- Move the Mountaineer Token onto an adjacent Mountain card, attempting to scale it. The mountaineer player rolls two six-sided dice. If the sum of the dice is greater than or equal to the Mountain card's Difficulty value, the mountaineer succeeds, drawing the card into their hand and moving the Mountaineer Token into the empty space. If they fail, they must remain on the empty space they were in before and they cannot attempt to scale any more obstacles this turn. They may still play Mountain cards from their hand.
- Play a Mountain card from their hand to gain its special effect. They take the action that is printed on the card before doing anything else. Certain cards can only be played at certain times, such as immediately after a die roll. Unlike the mountain player, the mountaineer player does not draw cards from the deck to replace cards they play. Except for special card effects, the only way for the mountaineer to draw cards is by picking them up from the board.

When the mountaineer player doesn't want to (or can't) do anything else, the turn passes back to the mountain player and the loop continues.

## Ending the Game

The game ends when the last card is drawn from the Mountain deck. When this happens, either during the mountain player's turn or the mountaineer player's turn, the game ends immediately and neither player can take any more actions.

Each player then reveals their Goal card and tallies up the points it gives them. Many Goal cards give points based on the Mountain cards the mountaineer crossed, which can be checked by combining the discard pile with the mountaineer player's hand of cards. Then the player with the most points wins!
