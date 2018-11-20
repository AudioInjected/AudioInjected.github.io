---
layout: post
title:      "My failed attempt at implementing min max"
date:       2018-11-20 01:50:15 +0000
permalink:  my_failed_attempt_at_implementing_min_max
---


I had a much easier time with the Tic Tac Toe AI lab than I did with the previous Tic Tac Toe lab. The instructions in the TTT AI lab for creating the AI mentioned something called the min max algorithm. The instructions also mentioned that it would be too difficult to implement for that particular lab. I tried to anyways.

So, the min max algorithm is designed for a two player game. The algorithm is recursive, meaning it calls itself. The algorithm goes through every possible move for the max player, in this case the AI, and every possible move for the min player, in this case a human player. The algorithm makes a move, checks if the game is over, and if it is not over it will call the min max method, make another move and checks if the game is over until there are no more moves to make. If the AI won it's +10, if the Human won it's  -10 and if it is a draw it is 0. Basically the AI will always choose the higher number. If the human player can win, the AI will go for a draw because 0 is higher than -10.  I'm pretty sure I messed up the basic explanation of this because I still don't fully understand the algorithm and how to use it. I tried to use it in my tic tac toe game but I just couldn't figure it out, especially with no tests to help me. I read articles and tried to follow along, and I think the closest I got to it was with a youtube video where someone made a tic tac toe game using Javascript. I am not as familiar with Javascript as I am with Ruby but it was much easier to understand then some code I found using a C language.

I will try to be able to use this algorithm eventually, and even though I spent hours trying to implement min max, I don't think the hours were wasted. I certainly know more then when I first looked it up and I know that if I keep coding and trying to implement min max, I will eventually get it.
