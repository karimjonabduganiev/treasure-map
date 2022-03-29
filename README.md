# treasure-map
Treasure Map program

We are going to write a program that will mark a spot with an X.

In the starting code, you will find a variable called map.

This map contains a nested list. When map is printed this is what the nested list looks like:

['⬜️', '⬜️', '⬜️'],['⬜️', '⬜️', '⬜️'],['⬜️', '⬜️', '⬜️']

In the starting code, we have used new lines (\n) to format the three rows into a square, like this:

['⬜️', '⬜️', '⬜️']

['⬜️', '⬜️', '⬜️']

['⬜️', '⬜️', '⬜️']

This is to try and simulate the coordinates on a real map.

Our job is to write a program that allows you to mark a square on the map using a two-digit system. The first digit is the vertical column number and the second digit is the horizontal row number. e.g.:


x = map[2][1]

['⬜️', 'X', '⬜️']
['⬜️', '⬜️', '⬜️']
['⬜️', '⬜️', '⬜️']

First, our program must take the user input and convert it to a usable format.

Next, you need to use it to update your nested list with an "x".



