
# Computer Science I 
## Lab 2.0 Worksheet

Name(s) and Login(s):
hafza waqas        hafzawaqas2004



1. Dennis Ritchie, the creator of the C programming language,
was born on September 9th, 1941.  If he were still alive,
how old would he be today?  Find out by running the `birthday`
program on the appropriate inputs and enter your solution here.

Dennis Ritchie  would be  82 years, 4 weeks, and 1 days old today




2. Bjarne Stroustrup, the creator of the C++ programming
language, the object-oriented extension of C, was born on
December 30th, 1950.  How old is he today?

You are 72 years, 40 weeks, and 3 days old today



3. Software testing often involves testing code with known
"bad" input in an attempt to break it (sometimes this is
referred to as *fuzzing*).  Try breaking the `birthday_cli`
program by giving it "bad" input and observe the consequences.
Give at least two examples of potentially bad input and the
results you observe.





4. Complete all the size and range entries below.

* `char`
  size: 1 byte
  range: -128 to 127
* `short int`
  size:2 bytes
  range:-32768 to 32767
* `int`
  size:4 bytes
  range:-2147483648 to  2147483647
* `long int`
  size:4 bytes
  range:-2147483648 to  2147483647
* `float`
  size:4 bytes
  range: 7 digits of accuracy
* `double`
  size:8 bytes
  range: 15 digits of accuracy


5. Use your working currency conversion to determine
the exchange amounts for the following inputs:

  a) $250.25

  b) $1,000.52

  c) $968,410.12



6. Suppose that you had used only `int` types
in your conversion program.  Would you be able
to use it to convert the US national debt
(which as of 2020 was \$26,009,754,625,487)?
Why or why not?

NO, we cant use 'int' data type to represent this number because it has a range limit . however we will use 'long int' data type for this.




7. Mixed types

a) Run the `area` program with 3 and 4 as inputs.  
What value do you get?  Is this result correct?
The area is 0.000000 square units. which is a wrong answer.

b) Execute the program again with inputs 3 and 5.
Does the program give correct results?  Why not?
The area is 0.000000 square units. which is also wrong because in the formula we have used 1/2 instead of 0.5 . which will give an invalid answer because the first fractional value will be neglected.


c) Fix the program by editing the `area.c` source
code so that the program produces correct results.

fixed