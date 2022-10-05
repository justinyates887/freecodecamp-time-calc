# Time Calculator

This is the boilerplate for the Time Calculator project. Instructions for building this project can be found at https://www.freecodecamp.org/learn/scientific-computing-with-python/scientific-computing-with-python-projects/time-calculator

My solution for this project can be found in time_calc.py. It passed all tests presented against it.

Initially, I struggled with finding a proper algorithm for returning the day of week when a starting day was provided. I was trying to add the index to (number of hours % 7). The final solution was to calculate the amount of days in the hours, and then add that to the index of the starting day % 7.
