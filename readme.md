# Introduction
The goal of this system is to provide an accurate high-level overview rating for players - basically, a summary showing the difficulty of a map. The system outputs a base value that is utilized for our ranking systems, but players mainly want insight on the difficulty of a song before playing it.

# Challenges

There's a list of challenges that we have to face when computing for difficulty, and most of these arise from subjectivity. Everybody has a different play-style, which in turn, affects their skill set. 
Players have different skill sets.
Not all players will agree because everyone has a different playstyle.
Annoying Actions: Vibro, LN.
Actions, Patterns, ect.
4K and 7K.

Averaging
It is very hard to determine an average for the ratings. We have to choose between how hard it is to"acc" or how hard it is to play on average.

# Process

## Optimization

We use Nelder Mead algorithm for optimization. It's included in the Accord.Math C# Library.
