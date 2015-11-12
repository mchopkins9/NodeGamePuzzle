# Node Game #

The node game is a game where there are K places with exactly one path connecting any two places (including connecting a place to itself). Each of these paths is given a color, which does not have to be unique to that path (i.e. two or more paths may have the same color). This means that there are N colors such that 1 <= N <= K(K+1)/2.

When the game begins, three players are placed in random places. One at a time, any player may take its turn (no order, and a player can move twice in a row). In a single turn a player may only move from the place it is currently occupying, to another place via only the path that connects these two places. Additionally, a player may only move along a path that has the same color as the one path that connects the other two players.

The goal of this game is to get all three players to occupy the same place. This application solves for the shortest sequence of moves to achieve this, or one of the shortest sequences of moves if there are more than one such sequences which are the same length.