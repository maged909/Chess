## C++ Chess Simulation

### Introduction of Project

Currently there are no dynamic user interface and functionality is tested
by command lines in the form of:

```
(StartPos, EndPos)
```

### How to Invoke the Program

`ChessMain.cpp` & `SampleGames.cpp` contains a collection of the mentioned
commands. The main `Chess` and `SampleGames` programs can be invoked by:

```shell
make (Chess|SampleGames)?
(Chess|SampleGames)
```

### Project Organisation

The implementation of the game engine could be found in `ChessBoard.(cpp|hpp)`,
while implementation of other classes (chess pieces, error handling class)
could be found in `/src`

A partial test suite is able to be found in `/test`, currently it contains
unit tests for the Pawn and Knight piece
