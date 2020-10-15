---
description: >-
  Simulator playing a solitaire game of Scrabble and attempting to score as many
  points as possible.
---

# Scrabble Game

**System Description**

* To created a Scrabble game simulator which allows detecting if words are valid or not. 
* Also to implement an AI to play words that maximize score according to tile/word bonuses and point values of letters.

**Architecture**

There are two primary components \(units of execution\) in this system.

1. **Server** - provides an interface for accessing, modifying game state, calculating and returning the best move.
2. **Client** - provides an interface for playing a game through a GUI and input current rack with a full 7 letters

