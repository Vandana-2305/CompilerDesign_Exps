START

1. Create a FLEX file.

2. Define patterns for:
      Identifiers
      Numbers
      Operators

3. Return the recognized tokens to BISON.

4. Create a BISON file.

5. Define tokens for identifiers and numbers.

6. Define operator precedence for:
      + -
      * /

7. Parse the arithmetic expression.

8. For each arithmetic operation:
      Create a new temporary variable.

9. Generate three-address code in the form:
      t1 = operand1 operator operand2

10. Continue generating temporary variables
    for intermediate results.

11. Assign the final temporary result to the
    destination variable.

12. Display the generated three-address code.

STOP
