# Multiplication Table

*Challenge by Jack Boffa, HHS &apos;14*

Write and submit a Python program that prints a multiplication table.
The user must be able to determine the width and height of the table 
before it is printed.

It may be simpler to start by printing a grid consisting of Xs rather 
than numbers. The grid program output could be something like this:

```
Width of multiplication table: 10
Height of multiplication table: 8

X X X X X X X X X X
X X X X X X X X X X
X X X X X X X X X X
X X X X X X X X X X
X X X X X X X X X X
X X X X X X X X X X
X X X X X X X X X X
X X X X X X X X X X
```

Once you've made the grid, expand the program to print real numbers. 
To make the table look nice, you should right-justify the numbers when 
you print them. This can be done using the format() function as such:

```python
print("The number is: {0:>3}".format(1))         # Prints "The number is:   1"
print("The number is: {0:>3}".format(12))        # Prints "The number is:  12"
print("The number is: {0:>3}".format(123))       # Prints "The number is: 123"
```

The final multiplication table should look like this:

```
Width of multiplication table: 10
Height of multiplication table: 8

  1   2   3   4   5   6   7   8   9  10
  2   4   6   8  10  12  14  16  18  20
  3   6   9  12  15  18  21  24  27  30
  4   8  12  16  20  24  28  32  36  40
  5  10  15  20  25  30  35  40  45  50
  6  12  18  24  30  36  42  48  54  60
  7  14  21  28  35  42  49  56  63  70
  8  16  24  32  40  48  56  64  72  80
```

    
