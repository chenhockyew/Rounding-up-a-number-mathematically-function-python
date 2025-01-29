# Rounding-up-mathematically-function-python
Could not find solution to round a number up with math without if statements,conditionals or in built functions so I tried to make one(in python)

How it works:
Uses x^(0^x) to act as a conditional, if x(For all values 0 and greater) representing the decimal place, is 0 or equivalent, the function will return 0 else it will return 1. The returned value is then added to the number's floor division by 1.

Example:
Number = 7.09
x = 0.09 #decimal value(Number Modulo 1)
Plug into function y = x^(0^x):
y = 0.09^(0^0.09)
  = 0.009^(0)
  = 1
Add y to Number's floor division:
Number(rounded up) = y + (7.09//1) 
                = 1 + 7
                = 8 (successfully rounded up!)

Now with an integer:
Number = 6
x = 0 #decimal value(Number Modulo 1)
Plug into function y = x^(0^x):
y = 0^(0^0)
  = 0^(1)
  = 0
Add y to Number's floor division:
Number(rounded up) = y + (6//1) 
                = 0 + 6
                = 6 (success, 6 does not round up as it is already a whole number)

Function's Graph:
<img width="1280" alt="image" src="https://github.com/user-attachments/assets/29cc3af2-f9d8-49aa-8b6d-dbd088882ad7" />

