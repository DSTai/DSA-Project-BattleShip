# BattleShip

## Introduction 
The purpose of this report is to provide an overview of our project, which involves the implementation of the Battleship board game (Human vs. Computer) using the C# programming language and the Unity game development engine. The project focuses on applying fundamental algorithms and data structures, with a particular emphasis on implementing a non-random move for the computer player. The report will highlight the significance of implementing Battleship using C#, Unity, and the algorithmic aspect of the computer player.

## Game Rule

The game is played on two grids, one for each player. The grids are typically square – usually 10×10 – and the individual squares in the grid are identified by letter and number.[10] On the grid, the player records their own shots. 
Before play begins, each player secretly arranges their ships on their primary grid. Each ship occupies a number of consecutive squares on the grid, arranged either horizontally or vertically. The number of squares for each ship is determined by the type of ship. The ships cannot overlap (i.e., only one ship can occupy any given square in the grid). The types and numbers of ships allowed are the same for each player. These may vary depending on the rules. The ships should be hidden from players sight and it's not allowed to see each other's pieces. The game is a discovery game which players need to discover their opponents' ship positions.[11] 
This game we create is based on the 1990 version of the rules specify the following ships[12] : \
No. &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
Class of ship 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Size \
1 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
Carrier &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
5 \
2 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;
Battleship &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
4\
3 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
Cruiser &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
3\
4 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
Submarine &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
3\
5 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
Destroyer &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
2


After the ships have been positioned, the game proceeds in a series of rounds. In each round, each player takes a turn to announce a target square in the opponent's grid which is to be shot at. The opponent announces whether or not the square is occupied by a ship. If it is a "hit", the "ocean" grid will be marked with a red color on the grid board. The attacking player marks the hit or miss on their own "tracking" or "target" grid. When all of the squares of a ship have been hit, the ship's owner announces the sinking of the ship. If all of a player's ships have been sunk, the game is over and their opponent wins.

## Contributing
```
NAME                    STUDENT ID
Trần Huỳnh Đức Tài      ITDSIU20132
Huỳnh Thanh Thảo        ITDSIU20126

