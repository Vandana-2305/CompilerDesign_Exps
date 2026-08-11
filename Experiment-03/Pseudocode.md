START

1. Create a FLEX file to recognize:
      Identifiers
      Digits
      Operators

2. Return the recognized tokens from FLEX to BISON.

3. Create a BISON file.

4. Define tokens:
      ID
      DIG

5. Define operator precedence:
      + and -
      * and /
      Unary -

6. Define grammar rules for:
      Expression + Expression
      Expression - Expression
      Expression * Expression
      Expression / Expression
      - Expression
      (Expression)
      ID
      DIG

7. Call yyparse() to parse the input expression.

8. If the input matches the grammar:
      Display "valid Expression".

9. Otherwise:
      Display "Invalid Expression".

STOP
