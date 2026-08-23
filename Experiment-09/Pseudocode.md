START

1. Create a FLEX file to tokenize:
      • Identifiers
      • Numbers
      • Operators
      • Assignment operator
      • Semicolon

2. Pass the recognized tokens from FLEX to BISON.

3. Create a BISON file with grammar rules for:
      • Assignment statements
      • Arithmetic expressions

4. Parse each expression.

5. For every arithmetic operation, check for optimization opportunities.

6. If both operands are constants:
      Perform Constant Folding.
      Replace the expression with its calculated value.

7. If an algebraic simplification rule applies:
      x + 0 → x
      x - 0 → x
      x * 1 → x
      x / 1 → x

8. If strength reduction applies:
      x * 2 → x + x

9. Display the optimization performed.

10. Display the optimized assignment statement.

11. Repeat the process for all input statements.

STOP
