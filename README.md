# Magic the gathering - Shuffle simulation

Simulating different strategies of shuffling a deck to find the optimal way to distribute your mana evenly.

## Methodology

1. We're going to work with decks of only 2 types of cards: mana and non-mana. The deck will be 25 mana and 35 non-mana cards, so 60 in total.

2. We'll create different configuration of decks. Since you often have clumps of mana when you put your cards back after a game, we'll try simulating decks with clumps of mana as well.

3. We'll simulate different combinations and amounts of shuffle types. We'll go with a combination of a riffle and over-hand shuffle.

3. We'll calculate a measurement of mana distribution in the deck. There are different ways of achieving this:
- An avg & std dev of the distance of one mana card to the next. Smaller std dev is better in this case.
- 

4. Now we can visualize our results
