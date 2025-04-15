## Log-and-Pow-Function-in-C
## Definition and Usage
The pow() function raises a number to the power of another number.

The pow() function is defined in the <cmath> header file.

## Syntax
One of the following:

pow(double base, double exponent);
pow(float base, float exponent);
Parameter Values
Parameter	Description
base	Required. The base of the power operation.
If this is an integer type then it will be treated as a double.
exponent	Required. The exponent of the power operation.
If this is an integer type then it will be treated as a double.


## The log10() function returns the base 10 logarithm of a number.

Tip: The base 10 logarithm indicates approximately how many digits the integer part of a number has. See how to use it to count digits in the example below.

The log10() function is defined in the <cmath> header file.

Syntax
One of the following:

log10(double number);
log10(float number);
Parameter Values
Parameter	Description
number	Required. Specifies the value to calculate the logarithm for.
If the value is negative, it returns NaN (Not a Number).
If the value is 0, it returns -infinity.
If this is an integer type then it will be treated as a double
