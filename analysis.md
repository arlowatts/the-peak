---
title: Quantitative Analysis
---

## Initial setup

The initial setup for the board consists of placing at most 5 cards onto the board with the condition that each card must be next to two cards and/or a card and an occupied space. This makes the initial combination of possibilities a huge number not taking into account the distinctness of the cards. The player may choose to play anywhere from a minimum of three cards to meet the requirement to a maximum of 5 cards. If three cards are played, the game can start with 4 distinct placements of cards. The cards would occupy a corner around the occupied space as that is the only way to meet the game’s rules. With four cards the possibilities extend exponentially as it allows an outward expansion of cards and with 5 cards there are so many arrangements that calculation becomes very difficult. This allows the game to have great variety between each play session. All these were assuming all cards were the same however with the distinct cards and different possibilities of drawing each, The Peak becomes a very variable game.

## Drawing cards

There are a total of 9 goal cards. Since each player draws two goal cards to start the game, there are 756 distinct ways to deal the goal cards.

There are a total of 35 mountain cards:
- 4 hiking trails
- 1 bear cave 
- 2 tectonic shifts
- 4 streams
- 1 rainstorm
- 2 lookouts 
- 2 waterfalls
- 1 gondola 
- 2 natural springs
- 2 stone steps
- 1 protected hallow
- 2 eroded slopes
- 4 wooden bridges 
- 1 portapotty 
- 1 hermit hut
- 2 food caches 
- 1 cold snap
- 2 sandstone cliff

With the mountain drawing 5 cards in their first turn, there are 321,161,640,503 unique starting hands of mountain cards.

## Dice rolls

The game is played with two six-sided dice. Each time the mountaineer rolls the dice, they can get any result between 2 and 12 with the following probabilities:
- 2: 1/36
- 3: 2/36
- 4: 3/36
- 5: 4/36
- 6: 5/36
- 7: 6/36
- 8: 5/36
- 9: 4/36
- 10: 3/36
- 11: 2/36
- 12: 1/36

## Play time and scores

A typical play session runs 10-15 minutes, with the scores averaging around 40-50 per player. In early playtesting, the mountaineer gained over 100 points - now this is only possible if the mountain player willingly plays high-value cards for the mountaineer to take. The score advantages made us tweak some values of elevation for cards and implement a new rule to give the mountain player more points, giving them points for each card left on the board at the end of the game.
