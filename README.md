# Outpost6

## Overview
Outpost6 is a turn-based board game, played on a 6x6 grid. The goal is to capture the enemy castle.

## Units

### Swordsman
The swordsman moves horizontally or vertically and attacks diagonally.

### Bowman
The bowman moves diagonally and attacks 2 fields horizontally or vertically, though it doesn't move to the attacked square.

### Horseman
The horseman moves and attacks horizontally, vertically and diagonally. It has 2 moves instead of 1.

### Castle
The castle does nothing.

### Outpost
The outpost can be placed on any turn instead of making a move. It can only be placed adjacent of another allied unit.

## Board Setup

### Legend
s = swordsman  
b = bowman  
h = horseman  
c = castle  

|   | 1 | 2 | 3 | 4 | 5 | 6 |
|---|---|---|---|---|---|---|
| 1 | c | b | x | x | x | x |
| 2 | h | s | x | x | x | x |
| 3 | s | x | x | x | x | x |
| 4 | x | x | x | x | x | x |
| 5 | x | x | x | x | s | b |
| 6 | x | x | x | s | h | c |
