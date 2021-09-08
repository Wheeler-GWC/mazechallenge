# mazechallenge
You may already be familiar with the concept of arrays (or "lists" if you're using Python). Array elements can be other 
arrays. These are called 2D arrays (or matrices).

If you have an array of 8 elements, and each element is an array of another 8 elements, you would have 64 elements in all.

You could even envision this as a chessboard where you have 8 rows with 8 spaces on each row.

This coding challenge is navigating a maze. You are given three inputs:

1. A 2D array representing the maze. Walls are given a value of "1" while open spaces are given a value of "0".

2. An array containing 2 elements representing the starting space of the maze. The first element is for the row, and the second is for the column. Since arrays start counting at 0, if your start position was 2 spaces to the right of the upper-left corner, the array would be [2, 0].

3. The same thing as above but for the ending position.

Things to keep in mind:

You can assume that both the starting position and the ending position have a value of "0".

You are allowed to modify the open spaces but not the walls. So if you've already visited a space with "0", you can keep track of it by changing it to a "#" for example.

What your function should return:

The challenge used by Facebook was a bit more complex, but I'm going to make it a little simpler. All you have to return is the number of steps in the shortest route from start to finish. You don't have to list what those steps are, just the number of steps.

Concepts to learn:

1. Arrays

2. Recursion
