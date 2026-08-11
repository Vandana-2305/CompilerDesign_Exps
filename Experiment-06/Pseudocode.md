START

1. Create a FLEX file.

2. Define a pattern to recognize numbers.

3. When a number is recognized:
      Store its value in yylval.
      Return NUM token.

4. Return operators and newline characters.

5. Create a BISON file.

6. Define NUM token.

7. Define operator precedence and associativity:
      + and -
      * and /
      Unary -

8. Define grammar rules for:
      Expression + Expression
      Expression - Expression
      Expression * Expression
      Expression / Expression
      Number

9. Perform the corresponding arithmetic operation
   during parsing.

10. Display the calculated result.

11. If an invalid expression is entered:
       Display an error message.

STOP
