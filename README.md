# my-html-game
- This project is an implementation of the popular BlackJack Card Game
- Example of what I want to deliver [24/7 blackjack](https://www.247blackjack.com/)
 this is simply an example of a game for educational purposes

## Rules
- For official [rules](https://www.officialgamerules.org/blackjack)
- 52 cards in a hand [Shuffle algorithm](https://stackoverflow.com/questions/2450954/how-to-randomize-shuffle-a-javascript-array)
- Chip values ($1, $10, $100, $500)

## Win state
- Player's card total > Dealer's card total after all bets

## Lose state
- If the player card total < dealer's card total

## [Mockups](mockup.drawio.png)

## Gameplay
- **NOTE**: Currently the only supported mode is single player vs the dealer
- The player's session (stored in LocalStorage) starts us out at balance $2000, for a production version we would need user registration and payment, but the MVP is the game itself
- buy-in minimum is $100 (see chip values in rules)
- The player is dealt an 2 up-cards (display total )
- Dealer is dealt 2 cards (1 up , 1 down) matches each of player(s) bet
- Player can choose a few actions (hit, stay, increase bet) - if card total > 21 dealer wins

## Needed assets
- Poker chips ($1, $10, $100, $500) if svg we can style it different colors
- Suit Icons (diamonds, hearts, spades, clubs)
- Face Card Icons (King, Queen, Jack) - possibly find all card assets...
- Money pot
- Down faced card for dealer
- Down faced deck

## Game mechanics
- figure out how to do player turns (initial bet, then dealing, then player actions, dealer actions)

## Out of Scope for MVP
- [options screen](options.png) for background music, about insurance, dealer hitting on 17, etc