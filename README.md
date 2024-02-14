# Pokerapp (Open-Source Poker App)
 
Creating an Open source poker application that will be powered by crypto. 

# How Game Works
The logic of the game follows:
-Each player is given 2 cards, faced down (Other plays don't see your cards). Before any cards are put on the table, there will be oppurtunity to place bets. Once they've dont that, the dealer puts 3 cards (community cards) down on the table.
-During each round, each player has the oppurtunity to bet. If players want to remain in this round, they would need to match the bet at the bare minimum. If they don't think they have a good "hand", they fold.
-After the round of bettingm the 4th community card is shown on the table.
-Another round of betting takes place, like in step 2.
-The final community catd is placed down on the table.
-Final round of betting takes place.
-Players show their cards and sees how the winner is.
This is the order of best hands:
-Royal Flush: A, K, Q, J, 10 all of the same suit.
-Straight Flush: 5 consecutive cards of the same suit (Ex: You have a 2 and a 3, and a 4, 5, and 6, are on the table -> ALL THE SAME SUIT)
-Four of a kind: 4 of the same cards (Ex: One of your two cards is a 2, and there are three 2s on the table)
-Full House: 3 of same # card + 2 of same # card (Ex: You have two 4s in your hand, and 3 6s come out on the table)
-Flush: 5 cards of same suit, order does not matter (Ex: You have 2 hearts in your hand, and 3 hearts come out on table)
-Straight: 5 cards in consecutive order, suit does not matter (Ex: you have a 3 and a 5, and a 2, 4, and 6 are on the table)
-Three of a kind: 3 of same cards in play (Ex: You have a 3, and two 3s come out on the table)
-Two pair: 2 pairs of same # (Ex: You have a 10 and a 3, and a 10 and 3 comes out on the table)
-One pair: 1 pair of same # (Ex: You have a 4 in your hand, and a 4 comes out)
-High card: If nothing above is met, whoeever has the highest valued card wins.
-The winner must recieve all the bets that were placed during this round.

# Example Cases
-Royal flush beats everything
-Flush beats Straight
-Four of a kind beats two pairs


# Dependencies
In the case of this game, you would need to have C++ installed on your computer, since that is was his project is written in. In order to edit his code, you would need a code editor on your computer.

Another dependency to consider is having your crypto wallet set up, considering the only form of payment is crypto. I'm not entirely sure how to do that, but I believe it is critical to have a detailed instructions on the logic as well as how the user's features. 


 **Current Release**
 <https://github.com/vintige/pokerapp/releases/tag/0.0.1>
