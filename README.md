# blackjack
A C# application with windows user interface for the game Blackjack (a.k.a 21).

```
Blackjack Game

TABLE

	PERSON
		DEALER
		PLAYER
			attr:
			HAND, CHIPS, BETS, ACCOUNT

	DECK
		CARD
		(Attr: Face,Suit,Value)
		Methods
			.get -> Face, Suit, Value
			.set ->

		HAND(PLAYER, CARD)
		Methods
			.compute -> bust, blackjack
			.split -> create another hand object
			.get -> show cards in hand so far
			.set ->
			.add -> add new card to hand

	CHIP (Attr: Value, Colour)

	BETS (Attr: PersonID, CHIP)
		Methods:
			.total -> value bet
			.get ->
			.set ->

	ACCOUNT(Attr: person id, amount)
		Methods:
			.get -> value
			.set ->
```
