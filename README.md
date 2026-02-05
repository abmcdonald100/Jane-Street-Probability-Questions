This is a set of probability/expected value problems presented in a Jane Street Mock Interview. 
Each part involves a 100-round casino game played between a player and a casino with a 20-sided fair die. The 1 is showing at the beginning.

In Part 1, in each round you can either roll the die or win the amount showing on the die. (If the die shows 9, you can either win $9 or roll).
In Part 2, it is the same except in any turn after you win money you must roll, without the option to win money.
In Part 3, it is the same as Part 1 (you can roll or cash on any turn) but if you cash the casino can re-roll before the next round.
In Part 4, same as Part 1 but you can only cash once in the game.

In each case, the goal is to determine the optimal strategy and the expected total payout with that strategy. My approaches involve reverse engineering from the end of the game.
This leads to exact solutions that would take hours to calculate by hand but are easily solved with recursion in Python.

The goal of the mock interview was to solve these problems approximately with expected value heurestics, and those lead to very good answers that are in line with typical trading thought-processes,
but my solutions here are exact.
