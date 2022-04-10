# take6
Re-creation of a German card game called 6 nimmit! in Java to allow 2 players to go head to head in a battle of wits!

The Take 6! computer game has a 4 x 6 board with a deck of 104 cards. The deck is shuffled and both players get a ten-card hand that they can each respectively see, but they cannot see the other player's hand. At the start of the game, the board has one card in each of the four rows faced up.
Each round begins with both players selecting a card of their choosing from their hand and placing it faced down. 

Once both players have done this, the cards are flipped over and the card with the lowest number goes first, automatically being placed into the row with the "smallest possible difference between the current last card and the new one," as stated by the rules of the game. Additionally, "the number of the card that is added to a row must be higher than the number of the current last card in that row," so our code automatically ensures that this is the case as well. 

When a row hits 6 cards, the player who placed the 6th card must take all the cards in the row, earning a number of points based on the number of cow heads on each card in the row. Just like golf, in this game, more points is a bad thing. If a player plays a card whose number is lower than the last card of each of the four rows, the player has a choice in which row to place the card, after which they must take all the cards in the row. This allows the player to chose a row that would net them the least amount of points.

After 10 rounds have been played and neither player has any card left, the game is over. The winner is the player with the least amount of points.
