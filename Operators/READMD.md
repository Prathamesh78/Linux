# Linux Operators Reference Guide

This guide provides a quick reference for common operators used in Linux command line operations.

## Arithmetic Operators

### Addition (+)

The addition operator is used to add numbers together.

Example:
``bash
echo $((5 + 3))
``
output : 8


### Subtraction (-)

The subtraction operator is used to subtract one number from another.

Example:
``bash
echo $((10 - 4))
``
output : 6


### Multiplication (*)

The multiplication operator is used to multiply numbers.

Example:
``bash
echo $((3 * 5))
``
output : 15


### Division (/)

The division operator is used to divide one number by another.

Example:
``bash
echo $((10 / 2))
``
output : 5


### Modulus (%)

The modulus operator gives the remainder of a division operation.

Example:
``bash
echo $((10 % 3))
``
output : 1


## Logical Operators

### AND (&&)

The AND operator is used to execute a command if both conditions are true.

Example:
``bash
[[1 -eq 1]] && echo "True"
``
output : True


### OR (||)

The OR operator is used to execute a command if either condition is true.

Example:
``bash
[[ 1 -eq 2 ]] || echo "False"
``
output : False


### NOT (!)

The NOT operator is used to negate the result of a command.

Example:
``bash
[[ ! 1 -eq 2 ]] && echo "Not equal"
``
output : Not equal


## Comparison Operators

### Equal (==)

The equal operator is used to check if two values are equal.

Example:
``bash
[[ 5 == 5 ]] && echo "Equal"
``
output : Equal


### Not Equal (!=)

The not equal operator is used to check if two values are not equal.

Example:
``bash
[[ 5 != 3 ]] && echo "Not equal"
``
output : Not equal


### Greater Than (>)

The greater than operator is used to check if one value is greater than another.

Example:
``bash
[[ 5 > 3 ]] && echo "Greater than"
``
output : Greater than


### Less Than (<)

The less than operator is used to check if one value is less than another.

Example:
``bash
[[ 3 < 5 ]] && echo "Less than"
``
output : Less than


### Greater Than or Equal To (>=)

The greater than or equal to operator is used to check if one value is greater than or equal to another.

Example:
``bash
[[ 5 -ge 5 ]] && echo "Greater than or equal to"
``
output : Greater than or equal to


### Less Than or Equal To (<=)

The less than or equal to operator is used to check if one value is less than or equal to another.

Example:
``bash
 [[ 3 -le 5 ]] && echo "Less than or equal to"
 ``
 output : Less than or equal to
 
