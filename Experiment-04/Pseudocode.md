START

1. Create a FLEX file.

2. Define patterns for:
      Letters
      Digits

3. Return:
      LET for letters
      DIG for digits

4. Create a BISON file.

5. Define tokens:
      LET
      DIG

6. Define grammar rules:
      Variable → Variable
      Variable → LET
      Variable → Variable LET
      Variable → Variable DIG

7. Start parsing using yyparse().

8. If the input starts with a letter and is followed by
   any number of letters or digits:
      Display "Valid variable".

9. Otherwise:
      Display "Invalid variable".

STOP
