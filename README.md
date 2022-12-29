A program that finds solution for the number round in [Countdown](https://en.wikipedia.org/wiki/Countdown_(game_show)). Written in Python.

## Requirements
- Python3

## Usage
```
python solver N N N N N N T
```
Where each `N` is one of the six numbers picked by the contestants, and `T` is the target number.

The program tries to find the shortest exact solution. If there is none, it outputs the one closest to the target.

## Options
`-f`/`--fast`: Output the first exact solution found. This dramatically reduce the computation time, but the solution isn't necessarelly the shortest.

`-m`/`--mode`: Specifies the output format:
- `steps`: one step per line
- `infix`: the whole formula in infix notation
- `rpn`: the whole formula in Reverse Polish Notation

## Licensing
The code for this project is licensed under the terms of the GNU GPLv3 license.
