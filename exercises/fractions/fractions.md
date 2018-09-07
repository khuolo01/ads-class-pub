# Fractions

1. Expand the textbook implementation of the class *Fraction* (see GitHub) and add methods `get_numerator()` and `get_denominator()` that return the numerator and denominator of a fraction. Numerator and denominator must be specified as private members of the class Fraction.
1. Implement `numerator` and `denominator` as properties.
1. Expand the textbook implementation of the class *Fraction* and implement the remaining simple arithmetic operators (`__sub__`, `__mul__`, and `__truediv__`).
1. Use the provided function `gcd()` to simplify the resulting fraction whenever possible.
1. Modify the constructor of the class *Fraction* so that it checks if the numerator and denominator are both integers. If either is not an integer, the constructor should raise an exception.