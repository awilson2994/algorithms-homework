# Homework Assignment 4

## Making Change

Given a denomination of coins, find the least number of coins used to make various amounts of change.

#### Usage

Compile with: `g++ dp_making_change.cpp -o change -std=c++11`

Run with no added parameters: `./change`

Note: This program opens a file called denominations.inp in order to know what type of denomination to use.

## Dijkstra's Algorithm

Find the shortest path from i to j given a plain of nodes and edges given to the program through and input.inp file that contains the distance matrix for the given country.

#### Usage

Compile with: `g++ dijkstra.cpp -o dijkstra -std=c++11`

Run with single OPTIONAL parameters: `./dijkstra 1`

0 - Default, will let the user pick the nodes to travel from and to

1 - will do a simple run with all combinations of the first 3 nodes to the last 3 nodes

Note: converter.py converts data sets from http://www.math.uwaterloo.ca/tsp/world/countries.html to a distance matrix that can be used as an input file for dijkstra.cpp.
