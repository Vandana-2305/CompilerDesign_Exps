PROCEDURE:

Create a file named cal.l and define patterns to identify numbers using regular expressions.

For matched digits, return the token NUM and store the number using yylval.

Create another file named cal.y to define grammar rules for arithmetic expressions using BISON.

Include operator precedence and associativity using %left and %right.

Add rules to evaluate expressions like E + E, E - E, E * E, and E / E.

Compile both files using the following commands:

    flex cal.l
    bison -d cal.y
    gcc lex.yy.c cal.tab.c -o calc -lfl

Run the compiled program:

    ./calc

Enter arithmetic expressions and view the result.

Test with multiple expressions to verify both valid and invalid cases.
