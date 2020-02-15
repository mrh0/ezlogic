# EzLogic
Even monkeys could do it.

# About

Evaluates simple logic expressions operating on 32bit integer values and returning a single integer value.
Intended to be used for Minecraft Redstone logic but could be adapted for other things.

By: mrh0 (aka MRHminer or hminer)

# Keywords:
```
low : 0
hight : 15
true : 1
false: 0
state : current/previous output.
rng : random integer number (0-15).
```

# Operators:
```
+ - * / % : add, subtract, multiply, divide, modulo.
= == != : equals, equals, not equals.
< > <= >= : less, greater, less or equals, greater or equals.
& | ^ ~ : bitwise and, or, xor, not.
<< >> <<< >>> : bitwise shift left, shift right, rotate left, rotate right.
&& : logical and (results in the greatest of the two operands or 0).
|| : logical or (results in the first of the two operands that is greater than 0).
! : logical not (results as 1 or 0).
```
