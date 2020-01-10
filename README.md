Alessandro Profenna
Sept. 8, 2019

This BlackJack game was created using VisualStudio 2019 and C++.
Open the BlackJack.sln file to open the project and compile it there.

Rules for my implementation of BlackJack:

Welcome to BlackJack!
This is a command line version of the game.
Only one player (the user) vs the dealer.

The goal is to have a hand value greater than the dealer's but less than or equal to 21.
If the player's hand value is greater but over 21, the player loses, and the same goes for the dealer.
In the result of a tie, or if both bust (value over 21), then the player's bet is returned.
If the player wins, they win double their bet, and if they lose, they lose their bet.

The player is asked for a bet and is dealt two cards. The dealer is also dealt two cards.
The player can manipulate a single hand in a round. The player has four possible options with their hand:

1) Stand: Do nothing, the round ends.

2) Hit: Be dealt another card to your hand. If the value of your hand is >=
to 21, the round ends.

3) Double Down: Doubles your bet and deals another card to your hand. The round then ends.

4) Split: This option is only available if your first two cards have equal rank. This will split your cards
into two separate hands, and split your bet between each hand. Then you play each hand as a separate round,
continuing with the hand you were currently playing.
You can only split once, with a maximum of two player hands.

When the player finishes manipulating each of their hands, the scores are calculated for each 
player hand vs the dealer's hand to see which hands win.

Screenshot:

![Screenshot](https://user-images.githubusercontent.com/15040875/72185115-122e8f00-33c0-11ea-8bdb-e2ff94a59bbc.PNG)
