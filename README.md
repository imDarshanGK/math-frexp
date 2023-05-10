# math-frexp
math.frexp

math.frexp(x)

* Input: Real number
* Return Type: A Tuple containing one floating-point number & one integer ( A tuple is simply an immutable list in python)

This function takes a real number x as an argument and returns a tuple with the first value as the mantissa(floating number) and the second value as the exponent(integer) i.e. it returns a tuple (m,e) such that x = m * 2e. Here, in this expression, the floating number m is known as the mantissa and the integer e is known as the exponent.

solution:

     (0.75, 4)
