Multiplication 5.0
------------------

Two numbers given as arguments are multiplied and the result will be shown in 
the terminal.

The new feature is that the numbers to be multiplied together can be given as
arguments at the command line when the program is invoked.

It will be assumed that the name of the program file after compilation will be

  multiply
  
If you chose a different name please use this one instead of "multiply".

Just invoke like

  ./multiply number1 number2

for example

  ./multiply 5.80 6.95

And the result will be shown on the terminal.

The numbers are represented as double- values.

If too few arguments are given, the program aborts without telling a result.

The interactive mode that enabled entering the numbers after invocation with
"in: " prompts got removed because the multiplication of two numbers 
certainly is not regarded as a big task and it was considered more comfortable 
to pass the two numbers just at the invocation.



Version history:
----------------

Version 5.0:

Implementation of data entry by giving arguments at invocation


Version 4.0:

Implementation of full user interaction to make it run without the usage of a debugger.


Version 3.0:

Replaced the data type of the numbers by double to increase precision of
calculations.


Version 2.0:

Changed the data type of the numbers to float so that fraction- numbers can be
used for the calculation.


Version 1.0:

Initial implementation

