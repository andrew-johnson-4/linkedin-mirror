# Floating Point Rounding Modes

IEEE floating-point numbers can be rounded using several modes. 
The possible rounding modes defined by the IEEE 754 standard are:

Round to nearest, ties to even (default): 
The floating-point number is rounded to the nearest representable value. 
If the number being rounded is exactly halfway between two representable values, 
the value whose least significant bit is even is chosen.

Round towards zero: 
The floating-point number is rounded towards zero (i.e., truncated).

Round towards positive infinity: 
The floating-point number is rounded up to the nearest representable value that is greater than or equal to the original value.

Round towards negative infinity: 
The floating-point number is rounded down to the nearest representable value that is less than or equal to the original value.

Round to nearest, ties to away from zero: 
The floating-point number is rounded to the nearest representable value. 
If the number being rounded is exactly halfway between two representable values, 
the value whose least significant bit is odd is chosen.
