# Kenny Rogers Kata

This is the kata that will help you know when to hold 'em, fold 'em, walk away, or run.  Or something.

The exercise is simple. Write a function that takes two poker hands and declares the winner (or a tie).

It might be worthwhile to think of this as a comparator function.  In fact, there's no reason that it can't just return -1, 0, 1 in classic comparator fashion.  And, if you are feeling really ambitious, go ahead and use it to sort an array of poker hands.

## Valid Poker Hands

Just for those of y'all who might need a refresher on the topic, here are the power hands ranked best to worst.

| Hand Rank       | Description                                                            |
| --------------- | ---------------------------------------------------------------------- |
| Five of a Kind  | five cards of the same rank                                            |
| Royal Flush     | A, K, Q, J, 10 of same suit                                            |
| Straight Flush  | five cards of same suit in order                                       |
| Four of a Kind  | four cards of the same rank                                            |
| Full House      | two cards or the same rank and three cards of the same rank            |
| Flush           | five cards of the same suit                                            |
| Straight        | five cards in order                                                    |
| Three of a Kind | three cards of the same rank                                           |
| Two Pair        | two cards of the same rank and two other cards of the same rank        |
| Pair            | two cards of the same rank                                             |
| High Card       | a card                                                                 |


## Bonus

In the event of a tie, some people like to use suit as a tie breaker.  Here are the suit orders from highest to lowest.

          Spades
          Hearts
          Clubs
          Diamonds

## Even More Bonus

Wild cards.  Add a list of wildcards to your funciton.  Hilarity ensues as the odds get all messed up.

## Hints

Don't build an object model up front to represent cards.  Just write enough code to compare two hands.  A good test to start with would be high card wins.


