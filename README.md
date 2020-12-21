# EzLogic
Even monkeys could do it.

# About

Evaluates simple logic expressions operating on 32bit integer values and returning a single integer value.
Intended to be used for Minecraft Redstone logic but could be adapted for other things.

By: mrh0 (aka MRHminer or hminer)

# Identifiers:
```
low : 0
high : 15
true : 1
false : 0
state : current/previous output.
rng : random integer number (0-15).
left : left input (0-15).
right : right input (0-15).
back : back input (0-15).
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
! : logical not (results in 1 or 0).
_ : boolean (results in 1 or 0).
```

# Examples:
```
'(rng % 2) * high' : 0 or 15
'_ high' : 1
'high == 15' : 1
'4 << 1' : 8
'256 >> 2' : 64
'!back' : not gate
'(left || right) && (!left || !right)' : xor gate
```
