# Tic tac toe 

## About this Kata ##

We would like you to write a class to keep track and score a game of [Noughts and Crosses](https://en.wikipedia.org/wiki/Tic-tac-toe) sometimes called "Tic tac toe".

We want you to write a class named ``TicTacToeBoard`` that represents and verifies the current state of the board. Moving and scoring is encapsulated within this class.

```
public enum GamePlayer
{
    Noughts,
    Crosses
}

public struct Position 
{
  public int X;
  public int Y;
}

public class TicTacToeBoard 
{
    // TODO: all state & behaviour goes here, as you deem appropriate
}
```

---

### Game moves

We first need a method to make a move:

```
public void Move(Position pos, GamePlayer player)
{
  // TODO:
}
```

- Verify that the position is within the board's boundaries
- Verify that the posiition isn't already taken
- Any other verification you deem appropriate

---

### Game termination

We need a method to determine if the game can be continued, i.e. if the board is full:

```
public bool IsTerminated()
{
  // TODO: 
}
```

- ``true`` if the game is ended
- ``false`` if moves can still be made

---

### Game state

Lastly, we also need a method to verify the board state

```
public GamePlayer? IsPlayerWin() 
{
  // TODO:
}
```

- If the instance shows a win for Noughts then return ``GamePlayer.Noughts``
- If the instance shows a win for Crosses then return ``GamePlayer.Crosses``
- If the instance shows a draw, or can be continued, then return ``null``


---

## We need unit tests!

We're hot on test driven development, in the pure style, and that means test first and test often. Remember your early tutorials on TDD? That's what we practice.

---

## Pairing up, communications and all that stuff

You'll be sharing your screen with someone else, and they will be assessing *everything.*

As you go through the kata, don't isolate yourself. Talk, and talk a lot. We want to hear your thinking. 

So if you've got a problem in year head, *talk out loud* (don't worry, we do not record!)

If you need to pause to collect your thoughts, *please say so*. 

---

## Questions you might want to think about

* Can you factor the code for elegance and readability?

* How would you test with the minimum number of tests and test cases?

* What is the best way to verify your tests are correct?

* Speed! What are the bottlenecks?

* If you could refactor the signatures, how would you do so and why? 

## Thanks

***Many thanks to @robcthegeek!***
