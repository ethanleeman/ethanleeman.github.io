---
layout: post
title: Brute Force Tic-Tac-Toe
---
As an exercise in some old-school Reinforcement Learning, I made an AI that plays Tic-Tac-Toe. 

The AI has a dictionary of all possible boards and an estimation of their expected values which are first set to be 0.5 unless
the game is won by a player. When it is training and plays a game, it will with high probability pick the move with the largest expected value of winning (exploitation). 
But with small probability, it will play a random move in order to find potentially better moves (exploration). After a game is finished, it updates
the expected value of all boards that it played exploitatively to the expected value of the board it made with the next move.

After about 30 seconds of training on my MacBook, the AI doen't lose. You can check out the python notebook (https://github.com/ethanleeman/TicTacToe/blob/master/TicTacToe.ipynb) to build the AI yourself and play against it.

