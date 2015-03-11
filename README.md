##Leap Year

The tricky thing here is that a leap year occurs:

```plain
on every year that is evenly divisible by 4
  except every year that is evenly divisible by 100
    unless the year is also evenly divisible by 400
```

For example, 1997 is not a leap year, but 1996 is.  1900 is not a leap
year, but 2000 is.

If your language provides a method in the standard library that does
this look-up, pretend it doesn't exist and implement it yourself.


### How to Run this Lab

+ Clone the repository
+ Open **index.html** in your browser to see the currently failing test specs you are to pass
+ Open the repository in your favorite text editor to explore the different files
+ Open **js\leap-year.js** and write the function(s) or lines of code to pass the tests
+ You could refresh **index.html** in your browser intermittently to see the status of test specs.


###Notes

For a delightful, four minute explanation of the whole leap year
phenomenon, go watch [this youtube video][video].

[video]: http://www.youtube.com/watch?v=xX96xng7sAE

+ Prior understanding of Javascript classes, returning, and conditional statements will be required to complete this exercise.

+ Remember that passing code is just the first step. The goal is to work towards a solution that is as readable and expressive as you can make
it.

+ Please make your solution as general as possible. Good code doesn't just pass the test suite, it works with any input that fits the specification.

Have fun!
