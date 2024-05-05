# BlackJack C++ Implementation 
Blackjack, also known as twenty-one, is the most widely played casino banking game in the world. Blackjack is a comparing card game between a player and dealer, meaning players compete against the dealer but not against other players. It is played with one or more decks of 52 cards. The objective of the game is to beat the dealer in one of the following ways:

Get 21 points on the player's first two cards (called a "blackjack" or "natural"), without a dealer blackjack;
Reach a final score higher than the dealer without exceeding 21; or
Let the dealer draw additional cards until his or her hand exceeds 21.

## Requirements

* Dealer will shuffle the deck of cards, and deal 2 cards to player and 2 cards to himself;<br>
* Only one card of the  dealer is upward i.e. only partial information about the deal hand is known to player;<br>
* Player has 2 options Hit OR Stand;<br>
* Dealer expose his concealed card. If dealer's current score is less than 17, dealer draw more cards from the deck;<br>
* If score exceeds 17 then dealer score is compared with Player's score and the one with the higher score wins the Game;<br>
* if dealer wins dealer will collect the bet else if player wins dealer will pay off the bet<br>

## Assumptions
* Every card of the deck has Rank and Suit.
  Rank: Ace,2,3,4,5,6,7,8,9,10,Jack,Queen,King;<br>
* Only single player is playing;<br>

## Example
```
******Game Start!******
deck:
1 ,2 ,3 ,4 ,5 ,6 ,7 ,8 ,9 ,10 ,10 ,10 ,10 ,
1 ,2 ,3 ,4 ,5 ,6 ,7 ,8 ,9 ,10 ,10 ,10 ,10 ,
1 ,2 ,3 ,4 ,5 ,6 ,7 ,8 ,9 ,10 ,10 ,10 ,10 ,
1 ,2 ,3 ,4 ,5 ,6 ,7 ,8 ,9 ,10 ,10 ,10 ,10 ,
******Deck Shuffled!******
deck:
10 ,5 ,4 ,8 ,9 ,4 ,4 ,10 ,10 ,2 ,10 ,8 ,1 ,
5 ,8 ,10 ,10 ,1 ,6 ,5 ,9 ,10 ,10 ,10 ,10 ,6 ,
6 ,5 ,10 ,3 ,3 ,2 ,10 ,4 ,8 ,1 ,7 ,10 ,1 ,
10 ,7 ,2 ,2 ,7 ,6 ,3 ,7 ,9 ,10 ,10 ,3 ,9 ,

******Player1's move*******
Player1's Hand
Card:4
Card:8
Non Blackjack, Hit or Stand?
Press H to draw a card, press S to stand.
H
Card:4
Card:8
Card:10

******Player2's move*******
Player2's Hand
Card:9
Card:4
Non Blackjack, Hit or Stand?
Press H to draw a card, press S to stand.
H
Card:9
Card:4
Card:8

******Player3's move*******
Player3's Hand
Card:4
Card:10
Non Blackjack, Hit or Stand?
Press H to draw a card, press S to stand.
H
Card:4
Card:10
Card:1
Non Blackjack, Hit or Stand?
Press H to draw a card, press S to stand.
H
Card:4
Card:10
Card:1
Card:5
Non Blackjack, Hit or Stand?
Press H to draw a card, press S to stand.
S
Card:4
Card:10
Card:1
Card:5

******Player4's move*******
Player4's Hand
Card:10
Card:2
Non Blackjack, Hit or Stand?
Press H to draw a card, press S to stand.
H
Card:10
Card:2
Card:8
Non Blackjack, Hit or Stand?
Press H to draw a card, press S to stand.
S
Card:10
Card:2
Card:8
******Turns end!******
Dealer Hand:
Card:10
Card:5
Dealer Hand:
Card:10
Card:5
Card:10
******Check Win******
Dealer Hand:
Card:10
Card:5
Card:10
Player1's Hand
Card:4
Card:8
Card:10
Player2's Hand
Card:9
Card:4
Card:8
Player3's Hand
Card:4
Card:10
Card:1
Card:5
Player4's Hand
Card:10
Card:2
Card:8
Player1 Bust, lose!
Player2 Wins, Blackjack!
Dealer Bust, Player Wins!
Dealer Bust, Player Wins!

```
