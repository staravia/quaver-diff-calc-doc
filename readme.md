# Introduction

The goal of this system is to provide an accurate high-level overview rating for players; which is basically a summary showing the difficulty of a map. In doing so, we hope to minimize the amount of disagreements players may have with the difficulty calculation (see: challenges). 

This process outputs an overall difficulty value that is utilized for our ranking systems, but players mainly want insight on the difficulty of a song before playing it.

## Complexity

Another important detail is to keep the computation complexity as low as possible. The current system uses a few O(n^3) algorithms, which is pretty bad for what its' doing. We hope to reduce the complexity down to O(n^2) or even O(n log n) if possible.

# Challenges

There's a list of challenges that we have to face, and most of these challenges arise from subjectivity. Everybody has a personalized play-style, which in turn affects their skill set. To minimize disagreements, the goal would be to get constant feedback from both new and veteran players in the Quaver community. 

It has been decided to base difficulty around how hard it is to "play" rather than how difficult it is to achieve perfect accuracy on a map. The saddle point of the rating system leans more towards difficulty rather than accuracy. This is to award players more for playing more difficult maps rather than grinding easier maps for accuracy.

## Vibro and Jump Trills

The biggest offender in some nameable difficulty calculation algorithms are **vibro** and **jump trills**. Because they are dense and easy to play, the difficulty calculation system is more prone to break.

> Explain our solution to this problem

## Long Notes

Long notes are also pretty difficult to calculate. Short releases, Technical releases, Inverse, ect.

> Explain our solution to this problem

## Stamina

Stamina is pretty difficult to calculate. Just having stamina in the system will heavily change a map's rating. Not having it in will make short maps over-rated.

> Explain our solution to this problem

# Process

## Actions

## Optimization

We use Nelder Mead algorithm for optimization. It's included in the Accord.Math C# Library.

> Explain how this works

### Benchmark Maps

We have a handful of benchmark maps selected.

## Tools

> Show tools and how to use them

# Want to contribute?

> Contact info and stuff