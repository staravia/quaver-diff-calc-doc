# Introduction
The goal of this system is to provide an accurate high-level overview rating for players; which is basically a summary showing the difficulty of a map. In doing so, we hope to minimize the amount of disagreements players may have with the difficulty calculation (see: challenges). 

This process outputs an overall difficulty value that is utilized for our ranking systems, but players mainly want insight on the difficulty of a song before playing it.

# Challenges

There's a list of challenges that we have to face, and most of these challenges arise from subjectivity. Everybody has a different play-style, which in turn affects their skill set. 

- Vibro
- Long Notes
- Jump Trills / Brackets

Actions, Patterns, ect.

4K and 7K.

Averaging / Stamina

We decided to base difficulty on how hard it is to "play" rather than how difficult it is to achieve perfect accuracy on a map. We want the saddle point of the rating system to award players more for playing harder maps rather than grinding for accuracy.

# Process

## Optimization

We use Nelder Mead algorithm for optimization. It's included in the Accord.Math C# Library.
